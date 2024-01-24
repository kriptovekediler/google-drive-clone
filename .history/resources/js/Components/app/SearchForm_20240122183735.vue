<template>
    <form class="w-[600px] h-[80px] flex items-center">
        <TextInput type="text" class="block w-full mr-2" 
        v-model="form.search" 
        autocomplete 
        placeholder="Search for filed and folders"
        />
        
    </form>
</template>

<script setup>
import TextInput from '../TextInput.vue';

</script>