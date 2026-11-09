<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kiki's Flying Library - Perpustakaan Digital</title>
    <!-- Google Fonts & FontAwesome Icons -->
    <link href="https://fonts.googleapis.com/css2?family=Fredoka+One&family=Nunito:wght@400;600;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    
    <style>
        :root {
            --bg-color: #fdf8f2;
            --primary-red: #d94b40;
            --navy-blue: #2c3e50;
            --bakery-gold: #f39c12;
            --soft-yellow: #fef5d1;
            --card-bg: #ffffff;
            --text-dark: #34495e;
            --text-light: #7f8c8d;
            --shadow: 0 8px 24px rgba(0,0,0,0.06);
            --radius: 16px;
        }

        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
            font-family: 'Nunito', sans-serif;
        }

        body {
            background-color: var(--bg-color);
            color: var(--text-dark);
            min-height: 100vh;
            display: flex;
            flex-direction: column;
        }

        /* Header & Navigation */
        header {
            background-color: var(--primary-red);
            color: white;
            padding: 1.2rem 2rem;
            box-shadow: 0 4px 15px rgba(217, 75, 64, 0.3);
            position: sticky;
            top: 0;
            z-index: 100;
        }

        .header-container {
            max-width: 1100px;
            margin: 0 auto;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        .logo {
            display: flex;
            align-items: center;
            gap: 12px;
            font-family: 'Fredoka One', cursive;
            font-size: 1.5rem;
            letter-spacing: 1px;
        }

        .logo i {
            font-size: 1.8rem;
            color: var(--soft-yellow);
        }

        .nav-stats {
            background: rgba(255, 255, 255, 0.2);
            padding: 8px 16px;
            border-radius: 20px;
            font-weight: 600;
            font-size: 0.95rem;
            display: flex;
            align-items: center;
            gap: 8px;
        }

        /* Hero Banner */
        .hero {
            background: linear-gradient(135deg, #2c3e50, #34495