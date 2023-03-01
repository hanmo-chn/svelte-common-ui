<script lang="ts">
    export let style: string = "";
    let className: string = "";
    export {className as class};
    export let text: string = '';

</script>
<label class="tsui-label {className}" {style}>
    {text}
</label>