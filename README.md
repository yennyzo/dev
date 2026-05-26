
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>OCaddup! - Character Profile</title>
    
    <style>
        /* Base page styling */
        body {
            background-color: #1a1a24; 
            color: #e0e0e6; 
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            margin: 0;
            padding: 20px;
        }

        /* Site header layout */
        header {
            text-align: center;
            background-color: #252533; 
            padding: 20px;
            border-radius: 12px;
            border-bottom: 3px solid #ff4a5a; 
        }

        header h1 {
            color: #ff4a5a; 
            margin: 0;
            font-size: 2.5rem;
        }

        /* Nav links */
        nav a {
            color: #00adb5; 
            text-decoration: none;
            font-weight: bold;
        }
        nav a:hover {
            color: #ff4a5a; 
        }

        /* Card holding the character data */
        .profile-card {
            display: flex;
            background-color: #252533;
            padding: 30px;
            margin: 30px auto;
            max-width: 800px;
            border-radius: 16px;
            box-shadow: 0 8px 24px rgba(0, 0, 0, 0.3);
            gap: 30px; 
        }

        /* Image frame styling */
        .oc-image-container img {
            border: 4px solid #3f3f57;
            border-radius: 12px;
            background-color: #1a1a24;
            object-fit: cover;
        }

        /* Detail section typography */
        .oc-details h2 {
            color: #00adb5;
            margin-top: 0;
            font-size: 2rem;
        }

        .oc-details h3 {
            color: #ff4a5a;
            border-bottom: 1px solid #3f3f57;
            padding-bottom: 5px;
        }

        /* Interactive tags list */
        ul {
            list-style: none;
            padding: 0;
            display: flex;
            gap: 10px;
            flex-wrap: wrap;
        }

        ul li {
            background-color: #3f3f57;
            padding: 6px 14px;
            border-radius: 20px;
            font-size: 0.9rem;
            border: 1px solid #ff4a5a;
        }

        /* Bottom button layout */
        .actions {
            text-align: center;
        }

        button {
            background-color: #ff4a5a;
            color: white;
            border: none;
            padding: 15px 30px;
            font-size: 1.1rem;
            font-weight: bold;
            border-radius: 30px;
            cursor: pointer;
            box-shadow: 0 4px 15px rgba(255, 74, 90, 0.4);
            transition: transform 0.2s, background-color 0.2s;
        }

        button:hover {
            background-color: #e03e4d;
            transform: scale(1.05); 
        }
    </style>
</head>
<body>

    <!-- Website Header -->
    <header>
        <h1>OCaddup!</h1>
        <p>Where artists find OC friends.</p>
        <nav>
            <a href="#">Home</a> | 
            <a href="#">Find Matches</a> | 
            <a href="#">My Gallery</a>
        </nav>
    </header>

    <!-- Main Profile Section -->
    <main>
        <section class="profile-card">
            <!-- Blank Image Slot -->
            <div class="oc-image-container">
                <img src="https://via.placeholder.com/300" alt="Character Drawing Placeholder" width="300" height="300">
            </div>

            <!-- Profile Info Fields -->
            <div class="oc-details">
                <h2>Character Name</h2>
                <p><strong>Creator:</strong> Your Name</p>
                
                <h3>Bio & Backstory</h3>
                <p>Write a brief summary of your character's personality, traits, and story here.</p>
                
                <h3>Style Tags</h3>
                <ul>
                    <li>Tag 1</li>
                    <li>Tag 2</li>
                    <li>Tag 3</li>
                </ul>
            </div>
        </section>

        <!-- Matching Trigger Button -->
        <section class="actions">
            <button onclick="alert('Running the Matcher logic...')">Find Artstyle Matches!</button>
        </section>
    </main>

    <!-- Site Footer -->
    <footer style="text-align: center; margin-top: 40px; color: #7f7f9c;">
        <p>&copy; 2026 OCaddup! - Strictly Hand-Drawn Art Only.</p>
    </footer>

</body>
</html>
