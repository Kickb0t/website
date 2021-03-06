
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    
<title>Online Instagram Profile Viewer - IGLookup</title>
<meta name="description"
    content="Start spying on private Instagram profiles here. Enter the Instagram username and get access to private photos and videos by our Instagram profile viewer.">
<meta name="robots" content="index,follow" />
<meta property="og:site_name" content="InstaGramies">
<meta property="og:url" content="https://www.iglookup.com/spy">
<meta property="og:title" content="Online Instagram Profile Viewer - IGLookup">
<meta property="og:description"
    content="Start spying on private Instagram profiles here. Enter the Instagram username and get access to private photos and videos by our Instagram profile viewer.">
<meta property="og:type" content="website">
<meta property="og:image" content="https://www.iglookup.com/static/img/social.jpg">
<meta name="twitter:site" content="@instagramies">
<meta name="twitter:card" content="summary">
<meta name="twitter:title" content="Online Instagram Profile Viewer - IGLookup">
<meta name="twitter:description"
    content="Start spying on private Instagram profiles here. Enter the Instagram username and get access to private photos and videos by our Instagram profile viewer.">
<meta name="twitter:url" content="https://www.iglookup.com/spy">
<meta name="twitter:image" content="https://www.iglookup.com/static/img/social.jpg">
<link rel="canonical" href="https://www.iglookup.com/spy">

    <link rel="icon" href="/static/img/favicon.ico">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bulma@0.8.0/css/bulma.min.css">
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css">
    <link href="https://fonts.googleapis.com/css?family=Roboto&display=swap" rel="stylesheet">
    <script src="https://code.jquery.com/jquery-3.4.1.min.js"></script>
    <style>
        /* body {
            font-family: 'Roboto', sans-serif;
        } */
        html {
            scroll-behavior: smooth;
        }

        #spimg:hover {
            cursor: pointer;
            transform: translateX(2px, 2px);
        }

        .feature {
            transition: all .3s ease-out;
        }

        .feature:hover {
            cursor: pointer;
            transform: scale(1.1);
        }

        .himg {
            position:relative; 
            width: 100%;
            top:0; 
            left:0;
            transition: all 0.3s ease-in-out;
        }

        .iicn {
            position:absolute; 
            top:50%; 
            left: 50%; 
            transform: translate(-50%, -50%);
            background-attachment: fixed;
            background:url('/static/img/download.png');
            background-size:cover;
            width:45px;
            height:45px;
        }

        .himg:hover {
            transform: scale(1.1);
            cursor: pointer;
        }

        #tab-content p {
            display: none;
        }

        #tab-content p.is-active {
            display: block;
        }

        #upic{
            font-size: 1em;
        }

        .window{
            white-space: nowrap;
            overflow: hidden;
            text-overflow: ellipsis;
        }
    </style>
</head>

<body>
    
<header>
    <nav class="navbar is-dark"
    style="background:linear-gradient(45deg, #405de6, #5851db, #833ab4, #c13584, #e1306c, #fd1d1d);">
    <div class="container">
        <div class="navbar-brand">
            <a class="navbar-item" href="/">
                <h1 class="title is-2 has-text-white">
                    <span class="icon">
                        <i class="fa fa-instagram has-text-danger"></i>
                    </span>
                    <span>IGLookup</span>
                </h1>
            </a>
            <div class="navbar-burger burger" data-target="navigation">
                <span></span>
                <span></span>
                <span></span>
            </div>
        </div>

        <div id="navigation" class="navbar-menu">
            <div class="navbar-start">
                <a class="navbar-item" href="/">
                    Home
                </a>
                <a class="navbar-item" href="/spy">
                    Spy Now
                </a>
                <a class="navbar-item" href="/#features">
                    Features
                </a>
                <!-- <a class="navbar-item" href="/">
                    FAQ
                </a> -->
            </div>

            <div class="navbar-end">
                <div class="navbar-item">
                    <div class="field is-grouped">
                        <p class="control">
                            <a class="bd-tw-button button is-info is-rounded" href="https://twitter.com/instagramies"
                                target="_blank">
                                <span class="icon">
                                    <i class="fa fa-twitter"></i>
                                </span>
                            </a>
                        </p>
                        <p class="control">
                            <a class="bd-fb-button button is-link is-rounded"
                                href="https://www.facebook.com/instagramies" target="_blank">
                                <span class="icon">
                                    <i class="fa fa-facebook"></i>
                                </span>
                            </a>
                        </p>
                    </div>
                </div>
            </div>
        </div>
    </div>
</nav>
</header>
<section class="hero is-small">
    <div class="hero-body">
        <div class="container">
            <div id="init">
                <h2 class="title is-1 has-text-centered">Start Instagram looker</h2>
                <br>
                <p class="subtitle is-4">Start using InstaGramies and instantly hack Private Instagram Accounts without
                    the use of any software or without any hacking experience.</p>
                <hr>
                <div class="columns">
                    <div class="column has-text-centered">
                        <div class="box">
                            <form>
                                <div class="control has-icons-left has-icons-right">
                                    <input class="input is-large is-rounded" type="url"
                                        placeholder="Enter Instagram Username" id="instauser" required>
                                    <span class="icon is-medium is-left">
                                        <i class="fa fa-instagram"></i>
                                    </span>
                                    <span class="icon is-medium is-right">
                                        <i class="fa fa-check"></i>
                                    </span>
                                    <small>ex: https://www.instagram.com/<strong>instagram</strong>/</small>
                                </div>
                                <hr>
                                <button class="button is-medium is-success" id="submit" type="submit">
                                    <span class="icon"><i class="fa fa-search"></i></span>
                                    <span>Access Profile</span>
                                </button>
                            </form>
                        </div>
                    </div>
                    <div class="column">
                        <div class="content is-medium">
                            <div class="box">
                                <strong>Instructions:</strong>
                                <ul>
                                    <li>Enter Instagram Profile Username.</li>
                                    <li>Click On Get Access Profile Button.</li>
                                    <li>Sit back and relax while tool works.</li>
                                    <li>Get the Result.</li>
                                </ul>
                            </div>
                        </div>
                    </div>
                </div>
                <hr>
            </div>

            <div id="gen" class="is-hidden">
                <div class="columns">
                    <div class="column is-12">
                        <div class="column is-12 has-text-centered">
                            <div id="fcontent">
                                <h3 class="title is-3">Accessing Please Wait...</h3>
                                <p class="subtitle">This may take some time.</p>
                                <progress class="progress is-large is-primary" max="100">40%</progress>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="columns">
                    <div class="column is-12">
                        <div class="message is-dark">
                            <div class="message-header has-background-info">
                                <span class="has-text-centered">Log Window</span>
                                <button class="delete"></button>
                            </div>
                            <div class="message-body has-background-dark box">
                                <div class="window">
                                    <div class="has-text-white has-text-weight-bold">
                                        <p class="font-weight-bold">**** InstaGramies Log Window V1.0.3****</p>
                                        <p id="date"></p>
                                        <script>
                                            document.getElementById("date").innerHTML = Date();
                                        </script>
                                        <p id="dots"></p>
                                    </div>
                                    <div class="has-text-success" id="typed3">

                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
            <div id="fopt" class="is-hidden">
                <div class="box">
                    <div class="columns">
                        <div class="column is-4 is-centered">
                            <figure class="image is-128x128" style="margin: auto;">
                                <img class="is-rounded" src="#" id="usrimg">
                            </figure>
                        </div>
                        <div class="column is-8">
                            <div class="is-flex">
                                <h3 class="title is-3" id="usrid"></h3>
                            </div>
                            <hr>
                            <div class="is-flex-mobile is-inline-tablet" style="margin-top: 15px;">
                                <span id="uposts" style="margin: 0px 10px 0px 10px;"
                                    class="has-text-weight-bold">0</span> posts
                                <span id="ufollowers" style="margin: 0px 10px 0px 10px;"
                                    class="has-text-weight-bold">0</span>
                                followers <span id="ufollowing" style="margin: 0px 10px 0px 10px;"
                                    class="has-text-weight-bold">0</span> following
                            </div>
                            <hr>
                            <div>
                                <p id="ubio"></p>
                            </div>
                        </div>
                    </div>
                    <hr>
                    <div class="box">
                        <div class="columns is-multiline" id="upic">

                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</section>
<hr>
<section class="section">
    <div class="container">
        <div class="box">
            <article>
                <div class="content is-medium has-text-centered">
                    <h2>How To Use</h2>
                    <hr>
                    <div class="columns">
                        <div class="column">
                            <div class="box feature">
                                <h3 class="subtitle">Enter username</h3>
                                <i class="fa fa-user fa-5x has-text-danger"></i>
                                <p>Enter the correct name of the user without error and get the details.</p>
                            </div>
                        </div>
                        <div class="column">
                            <div class="box feature">
                                <h3 class="subtitle">Click Access</h3>
                                <i class="fa fa-hand-pointer-o fa-5x has-text-danger"></i>
                                <p>Click access profile button and wait while we unlock profile for you.</p>
                            </div>
                        </div>
                        <div class="column ">
                            <div class="box feature">
                                <h3 class="subtitle">View Result</h3>
                                <i class="fa fa-eye fa-5x has-text-danger"></i>
                                <p>Online, you can view the photos and videos easily of the target account.</p>
                            </div>
                        </div>
                    </div>
                </div>
            </article>
        </div>
    </div>
</section>
<div class="modal" id="modal">
    <div class="modal-background"></div>
    <div class="modal-content has-background-white has-text-centered" style="padding: 15px;">
        <i class="fa fa-warning fa-5x has-text-danger"></i>
        <p class="title">Bot Like Beahivour Detected!!!</p>
        <p class="subtitle">Please Verify Captcha to continue.</p>
        <hr>
    </div>
</div>
<footer class="footer has-background-secondary" style="margin-top: 10px;">
    <div class="container">
        <div class="columns">
            <div class="column is-half">
                <p class="is-title is-size-4"><strong>IGLookup.com</strong></p>
                <p>
                    <strong>IGLookup</strong> help you to view the private profile of Instagram and easily you can
                    see the photos, videos by staying anonymous and keep updating yourself properly.
                </p>
                <br>
                <div class="d-inline has-text-centered">
                    <p class="subtitle">Follow Us</p>
                    <a href="https://www.facebook.com/iglookup">
                        <i class="fa fa-facebook fa-2x has-text-link"></i>
                    </a>
                    <a href="https://twitter.com/instagramies" style="margin-left: 10px;">
                        <i class="fa fa-twitter fa-2x has-text-info"></i>
                    </a>
                </div>

            </div>
            <div class="column is-one-quarter">
                <strong>Navigation</strong>
                <div class="has-text-left">
                    <ul class="menu-list">
                        <li><a href="/">Home</a></li>
                        <li><a href="/about">About</a></li>
                        <li><a href="/contact">Contact</a></li>
                    </ul>
                </div>
            </div>
            <div class="column is-one-quarter">
                <strong>Useful Links</strong>
                <div class="has-text-left">
                    <ul class="menu-list">
                        <li><a href="/privacy">Privacy</a></li>
                        <li><a href="/terms">Terms</a></li>
                        <li><a href="/disclaimer">Disclaimer</a></li>
                    </ul>
                </div>
            </div>
        </div>

        <div class="content has-text-centered">
            <p>&copy; 2019 - 2021 <strong><a href="/">IGLookup.com</a></strong></p>
            <p style="margin-top: -15px;">All rights reserved.</p>
        </div>
    </div>
</footer>

    
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/animate.css@3.5.2/animate.min.css">
<script src="/static/js/bulma.toast.min.js"></script>
<script src="/static/js/terminal.js"></script>
<script>
    var t1 = new Terminal();
    t1.setHeight("100%");
    t1.setWidth('100%');
    t1.setBackgroundColor('#363636');
    document.getElementById("typed3").appendChild(t1.html);

    document.getElementById("submit").addEventListener('click', () => {
        let iurl = document.getElementById("instauser").value;
        if (iurl != "") {
            location.href = "#";
            const udata = [];
            let is_private = "Private";

            $.ajaxSetup({
                headers: {
                    'Origin': `https://www.instagram.com/${iurl}`,
                    'accept': 'text/html,application/xhtml+xml,application/xml;q=0.9,image/avif,image/webp,image/apng,*/*;q=0.8,application/signed-exchange;v=b3;q=0.9',
                    'user-agent': 'Mozilla/5.0 (Linux; Android 6.0.1; Moto G (4)) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/89.0.4389.82 Mobile Safari/537.36',
                    'upgrade-insecure-requests': 1,
                    'Access-Control-Allow-Origin': '*',
                    'Access-Control-Allow-Methods': 'GET',
                    'Access-Control-Allow-Headers': 'application/json'
                },
                dataType: 'jsonp',
                contentType: 'application/json'
            });

            $.get(`https://www.instagram.com/${iurl}/?__a=1`, function (data, status, json) {
                console.log(data)
                if (data.graphql) {
                    bulmaToast.toast({ message: "Successfully Connected.", type: "is-success", duration: 5000, position: "center", animate: { in: "bounceIn", out: "fadeOut" } });
                    udata.push(data);
                    if (data.graphql.user.is_private == false) {
                        is_private = "Public";
                    }
                }
                else {
                    bulmaToast.toast({ message: "Something Went Wrong!!! Please Try Again.", type: "is-danger", duration: 5000, position: "center", animate: { in: "bounceIn", out: "fadeOut" } });
                    t1.print("Aborting connection...");
                    t1.print("Reloading Page!!!");
                    setTimeout(() => {
                        window.location.reload()
                    }, 5000)
                }
            }).fail(function () {
                bulmaToast.toast({ message: "Successfully Connected.", type: "is-success", duration: 5000, position: "center", animate: { in: "bounceIn", out: "fadeOut" } });
                udata.push(data);
                if (data.graphql.user.is_private == false) {
                    is_private = "Public";
                }
            });;

            document.getElementById("init").remove();
            document.getElementById("gen").classList.remove("is-hidden");

            var dotsl = setInterval(() => {
                document.getElementById("dots").innerHTML += "*";
            }, 1500);

            let cmd = ["Checking for available servers...",
                `Connecting to server ${Math.floor(Math.random() * 101)}...`,
                "Connection successfully established with server...",
                `curl -s -o /dev/null -I -w "%{http_code}" https://www.instagram.com/${iurl}`,
                "Valid Responce Received <200>",
                "Extracting Data...",
                "Data Successfully Extracted...",
                `${is_private} Profile Detected...`,
                `Accessing via API...`,
                `Access Gained Successfully...`
            ]

            var i = 0, howManyTimes = cmd.length;
            function addText() {
                t1.print(cmd[i]);
                i++;
                if (i < howManyTimes) {
                    setTimeout(addText, 5000);
                }
                if (i >= howManyTimes) {
                    clearInterval(dotsl);
                    t1.print("Bot Detected Captcha Verification Required!!!");
                    t1.print("Redirecting for verification!!!");

                    finalPage(udata);
                }
            }
            addText();
        }
    });

    function finalPage(udata) {
        if (udata[0]) {
            document.getElementById("gen").remove();
            document.getElementById("usrimg").src = udata[0].graphql.user.profile_pic_url_hd;
            document.getElementById("usrid").innerHTML = udata[0].graphql.user.username;
            document.getElementById("ubio").innerHTML = udata[0].graphql.user.biography;
            document.getElementById("uposts").innerHTML = udata[0].graphql.user.edge_owner_to_timeline_media.count;
            document.getElementById("ufollowers").innerHTML = notoMBK(udata[0].graphql.user.edge_followed_by.count);
            document.getElementById("ufollowing").innerHTML = udata[0].graphql.user.edge_follow.count;
            if (udata[0].graphql.user.is_private == false) {
                let data = createPicWall(udata[0].graphql.user.edge_owner_to_timeline_media.edges);
            }
            else {
                setTimeout(function () {
                    createHWall(udata[0].graphql.user.edge_owner_to_timeline_media.count);
                }, 3000);
                document.getElementById("upic").innerHTML = '<progress class="progress is-small is-primary" max="100">15%</progress>'
            }
            // document.getElementById("upic").innerHTML =
            document.getElementById("fopt").classList.remove("is-hidden");
        }
        else {
            // window.location.reload();
            capt();
        }
    }

    function createHWall(data) {
        var size;
        if (data >= 100) {
            size = 200
        }
        else {
            size = data;
        }

        let parent = document.getElementById("upic");

        var min = 0;
        var max = 182;

        setTimeout(function () {
            parent.innerHTML = '';
            for (var i = 0; i < size; i++) {
                var column = document.createElement("div");
                column.classList.add("column", "is-3", "himg");
                var image = document.createElement('img');
                image.src = `https://www.iglookup.com/static/insta/${Math.floor(Math.random() * 182) + 0}.jpg`;
                image.style = "object-fit: cover; object-position: center; width: 293px; height: 293px;";
                image.addEventListener("click", capt);
                // var dwn_btn = document.createElement("div");
                // dwn_btn.classList.add("v-ventered");
                var icon = document.createElement("span");
                icon.classList.add("iicn");
                column.appendChild(icon);
                column.appendChild(image);
                parent.appendChild(column);
            }
        }, 2000);
    }

    function capt() {
        document.getElementById("modal").classList.add("is-active", "animated", "bounceIn");
    }

    function createPicWall(data) {
        let parent = document.getElementById("upic");
        data.forEach(element => {
            var column = document.createElement("div");
            column.classList.add("column", "is-3", "himg");
            var image = document.createElement('img');
            image.src = element.node.display_url;
            image.style = "object-fit: cover; object-position: center; width: 293px; height: 293px;"
            // image.onclick = `onclick = window.open('${element.node.display_url}', '_blank');`
            image.addEventListener("click", () => { window.open(`${element.node.display_url}`, '_blank') });
            column.appendChild(image);
            parent.appendChild(column);
        });
    };

    function notoMBK(labelValue) {
        return Math.abs(Number(labelValue)) >= 1.0e+9
            ? Math.abs(Number(labelValue)) / 1.0e+9 + "B"
            : Math.abs(Number(labelValue)) >= 1.0e+6
                ? Math.abs(Number(labelValue)) / 1.0e+6 + "M"
                : Math.abs(Number(labelValue)) >= 1.0e+3
                    ? Math.abs(Number(labelValue)) / 1.0e+3 + "K"
                    : Math.abs(Number(labelValue));
    }

</script>
<script>
    $(document).ready(function () {
        $('#tabs li').on('click', function () {
            var tab = $(this).data('tab');
            $('#tabs li').removeClass('is-active');
            $(this).addClass('is-active');

            $('#tab-content p').removeClass('is-active');
            $('p[data-content="' + tab + '"]').addClass('is-active');
        });
    });
</script>
<script>
    $(document).ready(function () {
        $('#mod img').on('click', function () {
            document.getElementsByClassName("modal").classList.add("is-active", "is-clipped");
        });
    });
</script>

    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/js/bootstrap.min.js"></script>
    <script>
        (function () {
            var burger = document.querySelector('.burger');
            var nav = document.querySelector('#' + burger.dataset.target);

            burger.addEventListener('click', function () {
                burger.classList.toggle('is-active');
                nav.classList.toggle('is-active');
            });
        })();
    </script>
    <!-- Global site tag (gtag.js) - Google Analytics -->
    <script async src="https://www.googletagmanager.com/gtag/js?id=UA-153660446-1"></script>
    <script>
        window.dataLayer = window.dataLayer || [];
        function gtag() { dataLayer.push(arguments); }
        gtag('js', new Date());

        gtag('config', 'UA-153660446-1');
    </script>

</body>

</html>
