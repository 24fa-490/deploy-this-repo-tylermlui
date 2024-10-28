<script>
	export let container;
</script>

<div>
    <p><strong>Container Number:</strong> {container.containernumber}</p>
    <p><strong>Ship Name:</strong> {container.nameofship}</p>
    <p><strong>Container Size:</strong> {container.containersize}</p>
    <p><strong>Date Shipped:</strong> {container.datecontainershipped}</p>
</div>

<style>
	.row {
		display: flex;
		background-color: #eee;
	}
	.id,
	.shipname,
	.size,
	.date {
		margin: 5px;
	}
	.id {
		font-weight: bold;
		flex: 1;
	}
	.size {
		text-align: right;
		flex: 0 0 50px;
	}
	.date {
		flex: 0 0 100px;
		text-align: center;
	}
	.shipname {
		flex: 1;
		color: #999;
	}
</style>
