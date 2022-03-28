<template>
    <!-- <Tutorial/> -->
    <div>
        <!-- <Radio v-model="radio" label="1">备选项</Radio>
        <Tag type="success">标签二</Tag>

        <Badge :value="12" class="item">
            <Button size="small">评论</Button>
        </Badge>

        <Empty description="亲！这里什么都没有~"></Empty>

        <Empty image="https://shadow.elemecdn.com/app/element/hamburger.9cf7b091-55e9-11e9-a976-7f4d0b07eef6.png"></Empty>

        <Result title="404" subTitle="抱歉，请求错误">
            <template slot="icon">
                <Image src="https://shadow.elemecdn.com/app/element/hamburger.9cf7b091-55e9-11e9-a976-7f4d0b07eef6.png"></Image>
            </template>
            <template slot="extra">
                <Button type="primary" size="medium">返回</Button>
            </template>
        </Result>

        <Button :plain="true" @click="open2">成功</Button>-->

        <Button type="danger">危险按钮</Button>
    </div>
</template>

<script>
// import { Radio, Tag, Badge, Button, Empty, Result, Image } from 'element-ui';
import { Button } from 'vant';
export default {
    data() {
        return {
            radio: '1'
        };
    },

    methods: {
        open2() {
            this.$message({
                message: '恭喜你，这是一条成功消息',
                type: 'success'

            });
        },
    },

    components: {
        // Radio,
        // Tag,
        // Badge,
        Button,
        // Empty,
        // Result,
        // Image
    }
}
</script>
<style scoped>
.item {
    margin-top: 10px;
    margin-right: 40px;
}
</style>
