<template>
    <app-layout>


        <div class="py-3">
            <div class="max-w-7xl mx-auto sm:px-6 lg:px-8">
                <div class="bg-white overflow-hidden shadow-xl sm:rounded-lg">

                    <div class="alert alert-warning"
                        role="alert">
                        <div class="flex ">
                            <div class="py-1"><svg class="fill-current h-6 w-6 text-teal-500 mr-4"
                                    xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20">
                                    <path
                                        d="M2.93 17.07A10 10 0 1 1 17.07 2.93 10 10 0 0 1 2.93 17.07zm12.73-1.41A8 8 0 1 0 4.34 4.34a8 8 0 0 0 11.32 11.32zM9 11V9h2v6H9v-4zm0-6h2v2H9V5z" />
                                    </svg></div>
                            <div>
                                <p class="font-bold">서비스를 이용하기 위해서 추가정보를 입력해야 합니다!</p>
                                <p class="text-sm">빈칸 없이 입력해주세요!</p>
                            </div>
                        </div>
                        </div>
                        <div class="px-3 mx-auto">
                        <AddAuthForm />
                        </div>
                </div>
            </div>
        </div>
    </app-layout>
</template>

<script>
    import AppLayout from '@/Layouts/AppLayout'
    import AddAuthForm from '@/Jetstream/AddAuthForm'

    export default {
        components: {
            AppLayout,
            AddAuthForm,
        },
    }
</script>
