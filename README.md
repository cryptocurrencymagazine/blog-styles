# blog-styles
Collection of CSS styles for your blog

    body {
        display: flex;
        justify-content: center;
        align-items: center;
        height: 100vh;
        background-color: #f0f0f0;
    }
    .circle {
        width: 100px;
        height: 100px;
        border-radius: 50%;
        border: 5px solid gold;
        animation: rotate 3s infinite linear;
        box-shadow: 0 4px 20px rgba(0, 0, 0, 0.2);
        position: relative;
        overflow: hidden;
    }
    @keyframes rotate {
        from {
            transform: rotateY(0deg);
        }
        to {
            transform: rotateY(360deg);
        }
    }
    .face {
        width: 100%;
        height: 100%;
        position: absolute;
        top: 0;
        left: 0;
        background-image: url('YOUR_IMAGE_URL'); /* Replace with your actual image URL */
        background-size: cover;
        border-radius: 50%;
        opacity: 0.8;
    }
</style><style>
    body {
        display: flex;
        justify-content: center;
        align-items: center;
        height: 100vh;
        background-color: #f0f0f0;
    }
    .circle {
        width: 100px;
        height: 100px;
        border-radius: 50%;
        border: 5px solid gold;
        animation: rotate 3s infinite linear;
        box-shadow: 0 4px 20px rgba(0, 0, 0, 0.2);
        position: relative;
        overflow: hidden;
    }
    @keyframes rotate {
        from {
            transform: rotateY(0deg);
        }
        to {
            transform: rotateY(360deg);
        }
    }
    .face {
        width: 100%;
        height: 100%;
        position: absolute;
        top: 0;
        left: 0;
        background-image: url('YOUR_IMAGE_URL'); /* Replace with your actual image URL */
        background-size: cover;
        border-radius: 50%;
        opacity: 0.8;
    }

