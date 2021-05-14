<template>
    <!-- <h1>{{headerText}}</h1> -->
    <div>
        <slot>
            <h2>
            デフォルトのタイトル
            </h2>
        </slot> 
    </div>
</template>


<script>
export default {
    props:["headerText"],
}

</script>
