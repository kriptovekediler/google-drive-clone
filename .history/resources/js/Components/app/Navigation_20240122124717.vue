<script setup>
import ApplicationLogo from '../ApplicationLogo.vue';
import CreateNewDropDown from '@/Components/app/CreateNewDropDown.vue'
import { Link } from '@inertiajs/vue3';
</script>

<template>
    <nav class="min-w-[200px]">
        <div class="h-[80px] px-3 flex items-center gap-3">
            <Link href="/">
                <ApplicationLogo
                    class="block h-9 w-auto fill-current text-gray-800"
                  />
            </Link>
            LaraStorage
        </div>
        <div class="px-3">
            <CreateNewDropDown/>
            
            <div class="py-3">

            </div>
        </div>
    </nav>
</template>
