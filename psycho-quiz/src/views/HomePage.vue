<script>
import Option from '../components/Option.vue'

export default {
    components: {
        Option
    }
}
</script>
<template>
    <div class="h-screen text-center">
        <div class="h-full place-items-center">

            <div class="bg-slate-200 h-1/6">
                HEADERRRRR
            </div>
            <div class="bg-slate-400 h-5/6 place-items-center grid">Question
                <div class="bg-green-500 h-96 w-96 flex justify-evenly flex-col rounded-xl">
                    <Option class="mx-8 h-1/6" />
                </div>

            </div>
        </div>
    </div>
</template>