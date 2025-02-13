<script setup lang="ts">
const layout = "default";
</script>
<template>
    <NuxtLayout :name="layout">
        <div class="h-screen overflow-hidden">
            <div
                class="overflow-hidden h-full w-full absolute top-0 left-0 flex items-center object-contain"
            >
                <img src="/images/loginbg.svg" />
            </div>
            <div class="flex flex-col items-center justify-center">
                <div class="flex items-center justify-center">
                    <div class="flex-1 px-10 gap-4 flex flex-col">
                        <h1 class="text-4xl font-bold text-primary">
                            Restaurant Management
                        </h1>
                        <p>
                            Lorem ipsum dolor sit amet consectetur adipisicing
                            elit. Doloribus voluptatem laborum ipsam accusamus!
                            Quia minima minus, eos et repellendus fugiat sunt
                            maxime molestiae sequi quibusdam animi, suscipit,
                            quos perferendis similique.
                        </p>
                    </div>
                    <div
                        class="flex-1 flex items-center justify-center h-screen backdrop-blur-sm shadow-xl"
                    >
                        <LoginForm />
                    </div>
                </div>
            </div>
        </div>
    </NuxtLayout>
</template>
