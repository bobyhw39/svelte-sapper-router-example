<script>
	import Nav from 'sveltestrap/src/Nav.svelte'
	import NavItem from 'sveltestrap/src/NavItem.svelte'
	import NavLink from 'sveltestrap/src/NavLink.svelte'
	export let segment;
</script>

<Nav>
		<NavItem><NavLink href=".">Home</NavLink></NavItem>
		<NavItem><NavLink href="page2">Page 2</NavLink></NavItem>
		<NavItem><NavLink href="page3">Page 3</NavLink></NavItem>
		<NavItem><NavLink href="page4">Page 4</NavLink></NavItem>
</Nav>
