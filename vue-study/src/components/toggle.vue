<script lang="ts">
    import {Vue, Component} from 'vue-property-decorator';

    @Component
    export default class toggle extends Vue {
        public show: boolean = false;
        public toggle() {
            this.show = !this.show;
        }
    }
</script>