<template>
    <div>
        <el-row :gutter='12'>
            <el-card shado="hover">
                
                <router-link to="baseDecoder">base Decode</router-link>
            </el-card>
        </el-row>
    </div>
</template>
<script>
export default {
    data(){
        return{
            kinds:[
                'base'
            ]
        }
    }
}
</script>
