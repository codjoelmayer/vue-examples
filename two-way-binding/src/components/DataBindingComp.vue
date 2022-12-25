<template>
    <form >
        <div>
            <input type="text" id="entry-data" placeholder="Enter your data" v-model="entryData" required>
        </div>
        <div>
            <p >Entry data is: {{ entryData }}</p>
        </div>
    </form>
</template>

<script>
    export default {
        data() {
            return {
                entryData: null
            }
        },
        
    }
</script>