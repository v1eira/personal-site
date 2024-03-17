<script setup>
import { GithubOutlined, LinkedinOutlined, MailOutlined, MediumOutlined } from '@ant-design/icons-vue'
</script>

<template>
    <social-media-items>
        <a href="https://github.com/v1eira/" target="_blank" rel="noopener noreferrer">
            <GithubOutlined style="font-size: 24px;" />
        </a>
        
        <a href="https://www.linkedin.com/in/v1eira/" target="_blank" rel="noopener noreferrer">
            <LinkedinOutlined style="font-size: 24px;" />
        </a>

        <a href="mailto:ewersonv@gmail.com.br?subject=Let's connect!&body=Hey, Ewerson! I just saw your website and I want to connect.">
            <MailOutlined style="font-size: 24px;" />
        </a>
        
        <a href="https://medium.com/@v1eira" target="_blank" rel="noopener noreferrer">
            <MediumOutlined style="font-size: 24px;" />
        </a>
    </social-media-items>
</template>
  
<style scoped>
social-media-items {
    display: flex;
    align-items: center;
    justify-content: space-between;
    width: 160px;
}
a {
    width: 32px;
    height: 32px;
}
</style>
  