<template>
    <div class="bg-base-300 flex">
        <!-- <div class="relative z-10">
            <Navbar />
        </div> -->
        <div class="drawer lg:drawer-open">
            <input id="my-drawer-2" type="checkbox" class="drawer-toggle" />
            <div class="drawer-content">
                <div class="p-4">
                    <slot />
                </div>
            </div>
            <div class="drawer-side">
                <label
                    for="my-drawer-2"
                    aria-label="close sidebar"
                    class="drawer-overlay"
                ></label>
                <ul
                    class="menu bg-base-200 text-base-content text-md min-h-full w-80 p-4 flex-col flex gap-4"
                >
                    <li class="hover:bg-primary rounded-sm">
                        <NuxtLink to="/"> Menu</NuxtLink>
                    </li>
                    <li class="hover:bg-primary rounded-sm">
                        <NuxtLink to="/inventory"> Inventory</NuxtLink>
                    </li>
                    <li class="hover:bg-primary rounded-sm">
                        <NuxtLink to="/register"> Recipice</NuxtLink>
                    </li>
                    <li class="hover:bg-primary rounded-sm">
                        <NuxtLink to="/register"> Order</NuxtLink>
                    </li>
                    <li class="hover:bg-primary rounded-sm">
                        <NuxtLink to="/register"> User</NuxtLink>
                    </li>
                    <li class="hover:bg-primary rounded-sm">
                        <NuxtLink to="/register"> Table</NuxtLink>
                    </li>
                    <li class="hover:bg-primary rounded-sm">
                        <NuxtLink to="/register"> Reservation</NuxtLink>
                    </li>
                    <li class="hover:bg-primary rounded-sm">
                        <NuxtLink to="/register"> Logout</NuxtLink>
                    </li>
                </ul>
            </div>
        </div>
    </div>
</template>

<script setup lang="ts">
definePageMeta({
    layout: "default",
});
</script>
