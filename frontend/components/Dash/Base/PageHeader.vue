<template>
    <div class="page-header row no-gutters py-4">
        <div class="col-12 col-sm-4 text-center text-sm-left mb-0">
            <span class="text-uppercase page-subtitle">Dashboard</span>
            <h3 class="page-title">{{ page }}</h3>
        </div>
    </div>
</template>

<script>
export default {
    props: {
        page: String,
    }
}
</script>