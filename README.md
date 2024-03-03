






 <!DOCTYPE html>
 <html lang="en">
 
 <head>
     <meta charset="UTF-8">
     <meta name="viewport" content="width=device-width, initial-scale=1.0">
     <title>Hello World!</title>
     <link href="/test/styles/base.css" rel="stylesheet">
     <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
 </head>
 
 <body>
     <header class="container text-center my-4">
         <h1>Hello, World!</h1>
         <p>A fascinating journey in Tech...</p>
     </header>
     <main class="container">
         <section class="my-5">
             <p>I tried many things in life but true color came when I began to learn <strong>HTML</strong>, <strong>CSS</strong>, <strong>Bootstrap</strong>, and <strong>JavaScript</strong>, the rest is history!!!</p>
             <button id="coding-rocks" class="btn btn-primary mt-3">Coding Rocks!</button>
             <p id="more-story" class="d-none mt-3">Learning how to code is power and the possibilities are endless.</p>
         </section>
     </main>
     <script src="/scripts/main.js"></script>
 </body>
 
 </html>

body {
    background: linear-gradient(235deg,#4352B3,#000000,#FF00EA);
    font-family: 'Arial', sans-serif;
}

header h1 {
    color: #007BFF;
}

section p {
    font-size: 1.2rem;
    color: rgb(255, 254, 254);
}

p {
    color: white;
}

document.getElementById('coding-rocks').addEventListener('click', function() {
    document.getElementById('more-story').classList.toggle('d-none');
});


