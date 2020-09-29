<body class="bg-gray-200">
<div class="p-40">

    <div class="relative">

        <div>
            <span aria-label="Offline" 
                :aria-label="[true,false,false,true,false,true,true,false,true,false][value] ? 'Online' : 'Offline'"
                :class="{ 'bg-green-400':[true,false,false,true,false][value], 'bg-gray-200': !([true,false,false,true,false][value])}"
                class="flex-shrink-0 inline-block h-2 w-2 rounded-full bg-gray-200">
            </span>
        </div>
        <span x-text="["Harry Potter","Ron Weasely","Hermione Granger","Sirius Black","Bellatrix Lestrange"][value]">
        </span>

        <span class="inline-block w-full">
        <button type="button" aria-haspopup="listbox" aria-expanded="true" aria-labelledby="listbox-label" class="cursor-default relative w-full border border-gray-300 bg-white pl-3 pr-10 py-2 text-left focus:outline-none focus:shadow-outline-blue focus:border-blue-300 transition ease-in-out duration-150 sm:text-sm sm:leading-5">
            <div class="flex items-center space-x-3">
            <span aria-label="Online" class="bg-green-400 flex-shrink-0 inline-block h-2 w-2 rounded-full"></span>
            <span class="block truncate">
            Harry Potter
            </span>
            </div>
            <span class="absolute inset-y-0 right-0 flex items-center pr-2 pointer-events-none">
            <svg class="h-5 w-5 text-gray-400" viewBox="0 0 20 20" fill="none" stroke="currentColor">
                <path d="M7 7l3-3 3 3m0 6l-3 3-3-3" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round" />
            </svg>
            </span>
        </button>
        </span>
            
        <div class="absolute mt-1 w-full  bg-white">
        <ul tabindex="-1" role="listbox" aria-labelledby="listbox-label" aria-activedescendant="listbox-item-3" class="max-h-60 py-1 text-base leading-6 shadow-xs overflow-auto focus:outline-none sm:text-sm sm:leading-5">
            <li id="listbox-item-0" role="option" class="text-gray-900 cursor-default select-none relative py-2 pl-3 pr-9">
            <div class="flex items-center space-x-3">
                <span aria-label="Offline" class="bg-gray-700 flex-shrink-0 inline-block h-2 w-2 rounded-full"></span>
           
                <span class="font-normal block truncate">
                Ron Weasely 
                </span>
            </div>
            <span class="absolute inset-y-0 right-0 flex items-center pr-4">
             
                <svg class="h-5 w-5" viewBox="0 0 20 20" fill="currentColor">
                <path fill-rule="evenodd" d="M16.707 5.293a1 1 0 010 1.414l-8 8a1 1 0 01-1.414 0l-4-4a1 1 0 011.414-1.414L8 12.586l7.293-7.293a1 1 0 011.414 0z" clip-rule="evenodd" />
                </svg>
            </span>
            </li>
                    <li id="listbox-item-0" role="option" class="text-gray-900 cursor-default select-none relative py-2 pl-3 pr-9">
            <div class="flex items-center space-x-3">
                
                <span aria-label="Online" class="bg-green-400 flex-shrink-0 inline-block h-2 w-2 rounded-full"></span>
                
                <span class="font-normal block truncate">
                Hermione Granger
                </span>
            </div>
                        
            <span class="absolute inset-y-0 right-0 flex items-center pr-4">
            
                <svg class="h-5 w-5" viewBox="0 0 20 20" fill="currentColor">
                <path fill-rule="evenodd" d="M16.707 5.293a1 1 0 010 1.414l-8 8a1 1 0 01-1.414 0l-4-4a1 1 0 011.414-1.414L8 12.586l7.293-7.293a1 1 0 011.414 0z" clip-rule="evenodd" />
                </svg>
            </span>
            </li>
        </ul>
        </div>
    </div>
</div>
</body>


