<template>
    <div>
        <el-form ref="form" :model="form" label-width="auto" inline>
            <el-form-item label="活动名称">
                <el-input v-model="form.name"></el-input>
            </el-form-item>
            <el-form-item label="活动名称">
                <el-input v-model="form.name"></el-input>
            </el-form-item>
            <el-form-item label="活动名称">
                <el-input v-model="form.name"></el-input>
            </el-form-item>
            <el-form-item label="活动名称">
                <el-input v-model="form.name"></el-input>
            </el-form-item>
            <el-form-item label="活动名称">
                <el-input v-model="form.name"></el-input>
            </el-form-item>
            <el-form-item label="活动名称">
                <el-input v-model="form.name"></el-input>
            </el-form-item>
            <el-form-item label="活动名称">
                <el-input v-model="form.name"></el-input>
            </el-form-item>
        </el-form>
    </div>
</template>

<script>
export default {
    data () {
        return {
            form: {
                name: ''
            }
        }
    }
}
</script>