<template>
    <div>
        <tabs>
            <tab title="Options">
            </tab>
        </tabs>
        <p v-if="!subject" class="has-text-grey">No system selected</p>
    </div>
</template>

<script>
import HelloWorld from '../Common/HelloWorld.vue';
import Tab from '../Common/Tab.vue';
import Tabs from '../Common/Tabs.vue';
export default {
    props: ["subject"],
    components: { HelloWorld, Tabs, Tab },};
</script>

<style lang="scss" scoped>
</style>