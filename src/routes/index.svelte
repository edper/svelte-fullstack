<script>
    import TodoItem from '$lib/todo-item.svelte'
    const title = "Todos"
</script>
<svelte:head>
    <title>{title} List</title>
</svelte:head>
<h1>{title}</h1>
<form action="" method="">
    <input type="text" name="addToDo" id="" aria-label="Add a todo" placeholder="+ Tap to add a todo">
</form>

<TodoItem />
<TodoItem />
<TodoItem />