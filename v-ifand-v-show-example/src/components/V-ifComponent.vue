<template>
    <div class="container">
        <h2>v-if example</h2>
        <form class="form">
            <div class="row">
                <input class="form-control" type="number" id="inputNumber" v-model="inputNumber" placeholder="Enter a number" required>
            </div>
            <div class="row" v-if="(inputNumber % 2 == 0) && (inputNumber != null)">
                <label class="form-control">Even number</label>
            </div>
            <div class="row" v-else>
                <label class="form-control">Odd number / Empty</label>
            </div>
        </form>
    </div>
</template>

<script>
    export default {
        data() {
            return {
                inputNumber: null
            }
        },
    }
</script>

<style >

</style>