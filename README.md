# tributary-page1
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tributary Page</title>
    <style>
        body {
            background-color: blanchedalmond;
            /* margin: 20%;*/
            margin-left: 40px;
        }

        .img {
            height: 70px;
            object-fit: fill;
            width: 90px
        }

        #right {
            float: right;
            width: 400px;
            height: 389px;
            padding-left: 90px;
            padding-top: 36px;
            padding-right: 41px;
        }

        .info {
            box-sizing: border-box;
            display: inline-block;
            padding: 90px;
        }

        .navbar {
            background-color: bisque;
            border-radius: 10px;

        }

        #title {
            text-align: center;
        }

        .navbar li {
            float: right;
            list-style: none;
            margin: 20px 30px;
        }

        .IP {
            text-align: center;
            text-decoration: solid;
        }

        .navbar ul {
            overflow: auto;
        }

        .navbar input:hover {
            background-color: red;
        }


        .navbar li a:hover {
            background-color: aquamarine;
        }

        #img {
            display: flex;
        }

        .flex{
            display: flex;
            justify-content: space-around;
        }

        h4{
            padding-top: 10px;
        }

        .links{
            list-style: none;
        }

        #link{
            text-decoration: none;
            color: black;
        }


    </style>
</head>

<body>
    <header>
        <nav class="navbar">
            <ul class="links">
                <li ><a href="#" id="link">Life and career</a></li>
                <li ><a href="#" id="link">Photos</a></li>
                <li ><a href="#" id="link">Religious and political views</a></li>
            </ul>
        </nav>
        <main id="main">
            <h1 id="title"> VINAYAK DAMODAR SAWARKAR</h1>
            <div class="IP">Indian Politician</div>

            <hr>

            <section class="flex">
                <div id="img">
                    <img src="https://images-na.ssl-images-amazon.com/images/I/61f3qvVcdhL._SL1280_.jpg" id="right"
                        alt="image not processing">
                </div>
                <div id="info">
                    <h4><ul><li> Born 28 May 1883
                        Bhaghur,[1] Nasik district, Bombay Presidency, British India
                        (present-day Maharashtra, India)</li>
                        <br><li> Died 26 February 1966 (aged 82)
                        Bombay, Maharashtra, India</li>
                        <br><li> Known for Hindutva</li>
                        <br><li> Political party Hindu Mahasabha</li>
                        <br><li>Spouse Yamunabai
                        (m. 1901; died 1963)</li>
                        <br><li> Relatives Ganesh Damodar Savarkar (brother)</li>
                    </ul>
                    </h4>
                </div>
            </section><br><br><hr>

            <h1>About the Legend</h1>
            <div id="tribute-data">
                <p>Veer Savarkar was a great revolutionary in the history of India’s struggle of independence. He was a
                    great orator, scholar, prolific writer, historian, poet, philosopher and social worker.
                    His actual name was Vinayak Damodar Savarkar. He was born on May 28, 1883, in the village of Bhagpur
                    near Nasik. Ganesh (Babarao), his elder brother was a strong source of influence in his
                    At a very early age he lost his father Damodarpant Savarkar and mother Radhabai.</p>
                <p>Veer Savarkar established an organization by the name of ‘Mitra Mela’ which influenced the members to
                    fight for “absolute political independence” of India.
                    The Mitra Mela members served the victims of plague in Nasik. He later called the “Mitra Mela” as
                    “Abhinav Bharat” and declared “India must be independent”.</p>
                <p>The British Government withdrew Veer Savarkar’s graduation degree for his involvement in the Indian
                    freedom movement .In June 1906 he went to London to become Barrister. He wrote a book “The Indian
                    War of
                    Independence 1857” on India’s struggle of independence, which was banned by Britishers. When he was
                    in
                    London, he encouraged the Indian students in England against the British colonial masters.<br> He
                    supported the use of arms in India’s struggle of independence.</p>
            </div>

            <br><br>
            <div id="info1">
                For more information , check out <a href="https://en.wikipedia.org/wiki/Vinayak_Damodar_Savarkar"> <b>D
                        Sarvakar</b> </a>on Wikipedia
            </div>
        </main>
    
</body>

</html>
