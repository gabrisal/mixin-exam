<!-- 공통된 뷰가 없기 때문에 템플릿 태그가 없음 -->
<script lang="ts">
import { Vue, Component } from 'vue-property-decorator';

@Component
export default class Toggle extends Vue {
    public show: boolean = false;
    public toggle() {
        this.show = !this.show;
    }
}
</script>