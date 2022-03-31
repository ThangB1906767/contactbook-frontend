<template>
        <div class="page">
        <h4>Thêm liên hệ mới</h4>
        <ContactFormAdd />
        </div>
</template>

<script>
import ContactFormAdd from "@/components/ContactFormAdd.vue";
export default {
    components: {
        ContactFormAdd,
    },
    data() {
        return {
            contact: null,
            message: "",
            };
    }
};
</script>