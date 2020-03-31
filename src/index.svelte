<script>
    let price = ""
</script>

<h1 class="title">The Repeater</h1>

<label>
    Price without GST:
    <input bind:value={price}>
</label>

<p>Total Cost: ${Math.round(price * 1.15)}, rounded.</p>
