<style>
    body {
        margin: 0;
        font-family: Arial, sans-serif;
        background: #f4f7fa;
    }

    header {
        background: linear-gradient(90deg, #1e3c72, #2a5298);
        color: white;
        padding: 20px;
        text-align: center;
    }

    header h1 {
        margin: 0;
        font-size: 32px;
    }

    nav {
        display: flex;
        justify-content: center;
        background: #ffffff;
        padding: 10px;
        gap: 20px;
        flex-wrap: wrap;
    }

    nav a {
        text-decoration: none;
        color: #1e3c72;
        font-weight: bold;
    }

    .container {
        padding: 40px 20px;
        text-align: center;
    }

    .section-title {
        font-size: 26px;
        margin-bottom: 20px;
        color: #1e3c72;
    }

    .card-grid {
        display: grid;
        grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
        gap: 20px;
        padding: 20px;
    }

    .card {
        background: white;
        padding: 25px;
        border-radius: 10px;
        box-shadow: 0 4px 10px rgba(0,0,0,0.1);
        transition: 0.3s;
    }

    .card:hover {
        transform: scale(1.05);
    }

    .card h3 {
        margin-top: 0;
        color: #2a5298;
    }

    footer {
        background: #1e3c72;
        color: white;
        padding: 15px;
        text-align: center;
        margin-top: 40px;
    }
</style>
