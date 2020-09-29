<script>
    import UserSelector from './UserSelector.svelte'

    let selectedUserId = 'select'
    let selectedUserName = 'select'
</script>
<svelte:head>
    <link href="https://unpkg.com/tailwindcss@^1.0/dist/tailwind.min.css" rel="stylesheet"/>
</svelte:head>

<div class="flex">
	<div class='flex-1'>
    <UserSelector selectedUser={{userId: selectedUserId, name: selectedUserName}}/>
	</div>
</div>
        
 
