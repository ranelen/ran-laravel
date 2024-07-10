<template>
    <div class="navbar bg-green">
        <div class="container">
            <img src="../images/cloudiq.png" height="80px" class="logo">
            <div class="nav-menu d-flex">
                <a href="#" class="nav-link px-3 text-black">home</a>
                <a href="#" class="nav-link px-3 text-black">contact</a>
            </div>
        </div>
    </div>

    <div class="container py-5">
        <div class="hero d-flex justify-content-center align-items-center">
            <div class="text">
                <h1 class="title">“Transforming Vision into Reality”</h1>
                <button class="btn btn-primary bg-green text-black">learn more</button>
            </div>
            <div class="picture">
                <img src="../images/hero.png" width="600px">
            </div>
        </div>
    </div>

    <div class="info text-center py-5">
        <div class="container">
            <div class="d-flex flex-column align-items-center">
                <h2 class="title">service information</h2>
                <p class="desc" style="max-width: 80%;">At CloudIQ, we’re more than just developers. We’re a team of
                    visionaries
                    who
                    turn ideas into
                    reality. Whether it’s crafting elegant websites, building powerful mobile apps, or managing complex
                    projects, we thrive on making the impossible possible.</p>
            </div>

            <div class="cards d-flex justify-content-center flex-wrap text-start pt-5">
                <div class="card m-3 d-flex flex-column align-items-center p-3">
                    <img src="../images/web.svg" height="80px">
                    <h5>web development</h5>
                    <p>we excel in crafting robust and user-friendly websites.</p>
                    <ul>
                        <li>Front-End Development</li>
                        <li>Back-End Development</li>
                        <li>Responsive Web Design</li>
                    </ul>
                </div>

                <div class="card m-3 d-flex flex-column align-items-center p-3">
                    <img src="../images/mobile.svg" height="80px">
                    <h5>mobile development</h5>
                    <p>Our expertise extends to mobile app development for both iOS and Android platforms. We create
                        intuitive and feature-rich apps that resonate with your audience.</p>
                </div>

                <div class="card m-3 d-flex flex-column align-items-center p-3">
                    <img src="../images/project.svg" height="80px">
                    <h5>project management</h5>
                    <p>CloudIQ understands the importance of effective project management. Our services include:</p>
                    <ul>
                        <li>Methodologies</li>
                        <li>Project Planning</li>
                        <li>Risk Management</li>
                        <li>Communication Strategies</li>
                        <li>Quality Assurance</li>
                    </ul>
                </div>
            </div>
        </div>
    </div>

    <div class="contact py-5">
        <div class="container d-flex flex-column align-items-center">
            <h2>contact us</h2>
            <div class="form-group w-50">
                <input type="text" class="form-control my-3" name="" id="" aria-describedby="emailHelpId"
                    placeholder="full name">
                <input type="text" class="form-control mb-3" name="" id="" aria-describedby="emailHelpId"
                    placeholder="email address">
                <textarea class="form-control" name="" id="" rows="3" placeholder="how can we help you?"></textarea>
            </div>
        </div>
    </div>

    <footer class="bg-green py-3">
        <div class="container d-flex align-items-center">
            <img src="../images/cloudiq.png" height="100px">
            <span class="text-secondary me-lg-auto">cloudiq &copy all rights reserved.</span>

            <a href="https://www.facebook.com/ranelensalva.the8hoshi" class="nav-link">
                <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor"
                    class="bi bi-facebook" viewBox="0 0 16 16">
                    <path
                        d="M16 8.049c0-4.446-3.582-8.05-8-8.05C3.58 0-.002 3.603-.002 8.05c0 4.017 2.926 7.347 6.75 7.951v-5.625h-2.03V8.05H6.75V6.275c0-2.017 1.195-3.131 3.022-3.131.876 0 1.791.157 1.791.157v1.98h-1.009c-.993 0-1.303.621-1.303 1.258v1.51h2.218l-.354 2.326H9.25V16c3.824-.604 6.75-3.934 6.75-7.951" />
                </svg>
                facebook</a>
        </div>
    </footer>
</template>

<script>
export default {
    name: 'App'
};
</script>

<style>
body {
    background-color: #F3D0D7;
    font-family: "Fjalla One", sans-serif;
}

.card {
    max-width: 30%;
    min-width: 300px;
}
</style>