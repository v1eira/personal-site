<script setup>
import SocialMedia from './SocialMedia.vue'
</script>

<template>

    <page>
        <profile-image>
            <img src="../assets/me.jpg" alt="Ewerson">
        </profile-image>
        
        <content>
            <h1>Ewerson Vieira</h1>
            <h2>Software Engineer</h2>
            <summary>
                <p>
                    Experienced in Node.js, Go, PHP and Python.
                </p>
                <p>
                    Interested in system design, software architecture, scalable code and all the complexity that comes with it.
                </p>
                <p>
                    Always sharing what I study.
                </p>
            </summary>
            <SocialMedia />
        </content>
    </page>

</template>
  
<style scoped>
page {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: space-between;
}
img {
    width: 280px;
    height: 280px;
    border-radius: 0 36px 36px 36px;
    object-fit: cover;
    object-position: 100% 60%;
}
content {
    width: 300px;
    margin-left: 24px;
    display: flex;
    flex-direction: column;
}
h1 {
    font-size: 36px;
    color: #ffffff
}
h2 {
    font-size: 22px;
    color: #fff;
}
summary {
    font-size: 20px;
    margin: 20px 0;
}
p+p {
    margin-top: 18px;
}

@media (min-width: 380px) and (min-height: 800px) {
    page {
        margin-top: 4vh;
    }
}

@media (min-width: 400px) and (min-height: 900px) {
    page {
        margin-top: 6vh;
    }
}

@media (min-width: 700px) and (min-height: 940px) {
    page {
        margin-top: 12vh;
    }
}

@media (min-width: 1024px) {
    page {
        flex-direction: row;
        margin-top: 0;
    }
    img {
        width: 280px;
        height: 360px;
        border-radius: 36px 0 36px 36px;
        object-position: 100% 90%;
    }
    content {
        width: 600px;
    }
    h1 {
        font-size: 56px;
        color: #ffffff
    }
    h2 {
        color: #fff;
    }
    summary {
        font-size: 20px;
        margin: 20px 0;
    }
    p+p {
        margin-top: 6px;
    }
}
</style>
  