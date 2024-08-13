# TeenReads
<!DOCTYPE html>
<html lang="en">
<head> 
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>TeenReads</title>
    <link rel="stylesheet" href="{{ url_for('static', filename='styles.css') }}">
</head>
 <style> 
        body { 
            /* Background Color */
            background-color: Yellow;
       
        }
    </style>

<img src="WhatsApp Image 2024-08-09 at 18.27.28.jpeg" alt="Description" style="position: absolute; top:100000000000; right: 100000000000000000; width: 200px; height: auto;">


  <body>
<center>
  <header>
        <h1>TeenReads- Where you can find Excellent story books</h1>
        <nav>
            <ul>
                <li><a href="#books">Books Available</a></li>
                               <li><a href="#notes">Notes</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section id="hero">
            <h2>Enhancing Quality Education Worldwide</h2>
            <p>Join our community of educators, students, and parents to access top-notch resources and tools for educational excellence.</p>
        </section>
        <section id="books">
            <h2>Books Available</h2>
            <ul>
                <li><a href="https://posterspageturners.wordpress.com/wp-content/uploads/2017/04/we_were_liars.pdf" target="_blank">We Were Liars</a></li>
                <li><a href="https://primarysite-prod-sorted.s3.amazonaws.com/gobowen-primary-school/UploadedDocument/db3a2424ab834ade94f16606d5567712/the-hobbit-1.pdf" target="_blank">The Hobbit</a></li>
                <li><a href="https://kvongcmehsanalibrary.wordpress.com/wp-content/uploads/2021/07/harrypotter.pdf" target="_blank">Harry Potter</a></li>
                <li><a href="https://archive.org/details/LewisCSNarnia3TheHorseAndHisBoy/Lewis_C_S_-_Narnia_1_-_The_Magician_s_Nephew/page/n41/mode/2up" target="_blank">Chronicles of Narnia</a></li>
                <!-- Add more book links as needed -->
            </ul>
        </section>
        <section id="features">
            <h2>Our Features</h2>
            <div class="feature">
                <h3>For Readers</h3>
                <p>Find good story books- based on real life, and fiction.</p>
            </div>
            <div class="feature">
                <h3>Parental Involvement</h3>
                <p>Help your children increase their vocabulary and creativity.</p>
            </div>
        </section>
        <section id="notes">
            <h2>Notes</h2>
            <form action="{{ url_for('save_notes') }}" method="post">
                <textarea name="notes" id="notes-area" placeholder="Write your notes here...">{{ notes }}</textarea>
                <button type="submit">Save Notes</button>
            </form>
        </section>
    </main>
    <footer>
        <p>&copy; 2024 EduExcellence. All rights reserved.</p>
    </footer>
</body>
</html>
