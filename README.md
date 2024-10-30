<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="I SET SAIL - A Literary Collection">
    <title>I SET SAIL</title>
        html, body {
            height: 90%;
            margin: 0;
            font-family: 'Georgia', serif;
            background-color: #e9ebec;
            color: #3A3A3A;
            text-align: center;
            display: flex;
            flex-direction: column;
        }

        main {
            flex: 1;
        }

        header {
            padding: 2rem;
            background-color: #C5DFFB;
            background-image: url(https://i.pinimg.com/originals/bb/3a/cd/bb3acd2dac7a1ff05a7831da824042ea.jpg); 
            background-size: cover;
            background-position: center;
            color: white;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.4);
            border-radius: 0 0 20px 20px;
            width: 100%;
        }

        h1 {
            font-size: 4rem;
            letter-spacing: 3px;
            margin-bottom: 0.5rem;
        }

        p {
            font-size: 1.5rem;
            color: #E1EDF4;
            margin-top: 0;
        }

        .tabs {
            display: flex;
            justify-content: center;
            margin: 2rem 0;
        }

        .tabs a {
            text-decoration: none;
            padding: 1rem 2rem;
            color: #1C6BA0;
            background-color: #E1EDF4;
            border: 2px solid #1C6BA0;
            margin: 0 1rem;
            border-radius: 8px;
            transition: background-color 0.3s ease, color 0.3s ease;
        }

        .tabs a:hover {
            background-color: #1C6BA0;
            color: white;
        }

        .tabs a:target, .tabs a.active {
            background-color: #1C6BA0;
            color: white;
            font-weight: bold;
        }

        section {
            display: none;
            padding: 2rem;
            background-color: #ffffff;
            border: 1px solid #D8E2EB;
            border-radius: 8px;
            margin: 2rem auto;
            width: 80%;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
            text-align: center;
            line-height: 1.6;
        }

        section:target {
            display: block;
        }

        section h2 {
            font-size: 2.5rem;
            color: #1A567E;
        }

        section p {
            font-size: 1.2rem;
            color: #4A6A85;
        }

        footer {
            padding: 1.5rem;
            background-color: #4090be;
            background-size: cover;
            background-position: center;
            color: #587994;
            width: 100%;
        }

        @media (max-width: 768px) {
            .tabs {
                flex-direction: column;
            }
            .tabs a {
                margin: 1rem 0;
            }
            section {
                width: 95%;
            }
        }
    </style>
</head>
<body>

    <header>
        <h1>I SET SAIL</h1>
        <p>Author: LetYourPen_</p>
    </header>

    <main>

        <div class="tabs">
            <a href="#home" class="active">Home</a>
            <a href="#essays">Essays</a>
            <a href="#poems">Poems</a>
            <a href="#books">Books</a>
        </div>

        <section id="home">
            <h2>Hello! Welcome to this Collections</h2>
            <p>I am LetYourPen, and this is "I Set Sail." When I picture sailing, I see a boat moving into ocean, leaving the shore behind. Life, like the ocean, has calm days and storms. "I Set Sail" is about courage—about stepping into the unknown, facing whatever comes, and discovering what lies beyond the horizon.</p>
        </section>
        
        <section id="essays">
            <h2>Essays</h2>
            <div class="tabs">
                <a href="#essay1">Essay 1</a>
                <a href="#essay2">Essay 2</a>
                <a href="#essay3">Essay 3</a>
            </div>
        </section>

        <section id="essay1">
            <h2>Reflections on Nature</h2>
            <p>Exploring the depth of nature's beauty...</p>
        </section>
        <section id="essay2">
            <h2>Philosophy of Love</h2>
            <p>Discussing love's complexities...</p>
        </section>
        <section id="essay3">
            <h2>Paths of Growth</h2>
            <p>A journey through personal development...</p>
        </section>

        <section id="poems">
            <h2>Poems</h2>
            <div class="tabs">
                <a href="#poem1">1</a>
                <a href="#poem2">2</a>
                <a href="#poem3">3</a>
                <a href="#poem4">4</a>
                <a href="#poem5">5</a>
                <a href="#poem6">6</a>
                <a href="#poem7">7</a>
                <a href="#poem8">8</a>
                <a href="#poem9">9</a>
                <a href="#poem10">10</a>
            </div>

            <div class="tabs">
            <a href="#poem11">11</a>
                <a href="#poem12">12</a>
                <a href="#poem13">13</a>
                <a href="#poem14">14</a>
                <a href="#poem15">15</a>
                <a href="#poem16">16</a>
                <a href="#poem17">17</a>
                <a href="#poem18">18</a>
                <a href="#poem19">19</a>
                <a href="#poem20">20</a>
            </div>

            <div class="tabs">
            <a href="#poem21">21</a>
            <a href="#poem22">23</a>
            <a href="#poem24">24</a>
            <a href="#poem25">25</a>
            </div>

        </section>

        <section id="poem1">
            <h2>Across the Horizon</h2>
            <p>The waves call softly, a distant lullaby...</p>
        </section>
        <section id="poem2">
            <h2>The Whispering Tide</h2>
            <p>With each crest, the ocean speaks...</p>
        </section>
        <section id="poem3">
            <h2>Beneath the Blue</h2>
            <p>Down below, where the sunlight fades...</p>
        </section>

        <section id="books">
            <h2>Books</h2>
            <div class="tabs">
                <a href="#book1">Book 1</a>
                <a href="#book2">Book 2</a>
                <a href="#book3">Book 3</a>
            </div>
        </section>

        <section id="book1">
            <h2>Journey of the Heart</h2>
            <p>An exploration of human emotions...</p>
        </section>
        <section id="book2">
            <h2>Oceans of Time</h2>
            <p>A historical tale of love and loss...</p>
        </section>
        <section id="book3">
            <h2>Waves of the Soul</h2>
            <p>A collection of soulful poems and reflections...</p>
        </section>
    </main>

    <footer> 
        <p>© 2022 Literary Collection | LetYourPen_ </p>
    </footer>
    
</body>
</html>
