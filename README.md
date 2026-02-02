<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
<link href="https://fonts.googleapis.com/css2?family=Fredoka:wght@400;600&family=Quicksand:wght@400;600;700&display=swap" rel="stylesheet">

<style>
    :root {
        --pink-dark: #d63384;
        --pink-medium: #f687b3;
        --pink-light: #fbcfe8;
        --pink-soft: #fff1f2;
    }

    body {
        font-family: 'Quicksand', sans-serif;
        background-color: var(--pink-soft);
        color: #4d002b;
    }

    /* Navigasi Pink */
    .navbar {
        background-color: #ffffff !important;
        border-bottom: 3px solid var(--pink-light);
    }
    .navbar-brand, .nav-link {
        color: var(--pink-dark) !important;
        font-weight: 700;
    }
    .nav-link:hover {
        color: var(--pink-medium) !important;
    }

    /* Header Hero */
    header {
        background: linear-gradient(135deg, var(--pink-dark), var(--pink-medium));
        color: white;
        padding: 80px 0;
        text-align: center;
        border-bottom-left-radius: 50px;
        border-bottom-right-radius: 50px;
    }

    /* Profile Card */
    .main-card {
        background: white;
        border-radius: 30px;
        box-shadow: 0 10px 25px rgba(214, 51, 132, 0.2);
        margin-top: -60px;
        padding: 40px;
        border: 2px solid var(--pink-light);
    }

    /* Tempat Foto */
    .photo-frame {
        width: 200px;
        height: 200px;
        margin: 0 auto 20px;
        border: 6px solid var(--pink-light);
        border-radius: 20px;
        overflow: hidden;
        background-color: #fce7f3;
        display: flex;
        align-items: center;
        justify-content: center;
    }
    .photo-frame img {
        width: 100%;
        height: 100%;
        object-fit: cover;
    }

    /* Motivasi Box */
    .motivation-box {
        background-color: var(--pink-soft);
        border: 2px dashed var(--pink-dark);
        border-radius: 15px;
        padding: 20px;
        margin: 20px 0;
    }
    .motivation-text {
        font-style: italic;
        font-size: 1.1rem;
        color: var(--pink-dark);
        font-weight: 600;
    }

    /* Kurikulum List */
    .list-pink li {
        background-color: white;
        border-left: 5px solid var(--pink-dark);
        margin-bottom: 10px;
        padding: 10px;
        list-style: none;
        box-shadow: 2px 2px 5px rgba(0,0,0,0.05);
    }

    /* Footer Pink */
    footer {
        background-color: var(--pink-dark);
        color: white;
        padding: 30px 0;
        margin-top: 50px;
        text-align: center;
    }
    footer a {
        color: var(--pink-light);
        text-decoration: none;
    }
</style>
