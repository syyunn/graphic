<script>
import Chart from './Chart.vue';

export default {
    extends: Chart,
    props: {
        type: {
            type: String,
            default: 'column'
        },
        directLabel: {
            type: Boolean,
            default: true
        }
    }
};
</script>
