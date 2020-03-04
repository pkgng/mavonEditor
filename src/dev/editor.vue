<template>
    <div id="editor">
        <mavon-editor style="height: 100%" :subfield="false" defaultOpen="preview"></mavon-editor>
    </div>
</template>
<script>
module.exports = {
    name: 'editor',
    data: function() {
        return {

        };
    },
    computed: {
    },
    methods: {
    }
}
</script>
<style>
#editor {
  margin: auto;
  width: 80%;
  height: 580px;
}
</style>
