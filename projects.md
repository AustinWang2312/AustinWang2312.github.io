---
layout: default
title: Projects
permalink: /projects/
---
<img src="/assets/projects.jpg" class="collapsible-image" > 
<div style="height:100px"></div>
<div class="large-block">
    <div style="width:28%;display:block;float:left;">
        <div class="index-box">
            <h2>Project Index</h2>
        </div>
        <div class="index-box">
            <a href="#lyricloud" style="text-decoration:none;">Lyricloud</a>
            <p>
                2022 | Languages: Javascript, HTML, CSS
            </p>
        </div>
        <div class="index-box">
            <a href="#cookies" style="text-decoration:none;">Cookies.co Sales Analysis and Prediction</a>
            <p>
                2021 | Languages: Python
            </p>
        </div>
        <div class="index-box">
            <a href="#nobel" style="text-decoration:none;">Nobel Laureate JSON Web-service API</a>
            <p>
                2021 | Languages: PHP, SQL, Python
            </p>
        </div>
        <div class="index-box">
            <a href="#movie" style="text-decoration:none;">Movie/Actor Database System</a>
            <p>
                2021 | Languages: PHP, SQL
            </p>
        </div>
        <div class="index-box">
            <a href="#google" style="text-decoration:none;">Google Places Application Server Herd</a>
            <p>
                2021 | Languages: Python
            </p>
        </div>
        <div class="index-box">
            <a href="#simple" style="text-decoration:none;">Simple Router Implementation</a>
            <p>
                2021 | Languages: C++
            </p>
        </div>
        <div class="index-box">
            <a href="#stock" style="text-decoration:none;">Stock Price Prediction with CNN articles</a>
            <p>
                2020 | Languages: Python
            </p>
        </div>
        <div class="index-box">
            <a href="#delivery" style="text-decoration:none;">Delivery Navigation in LA</a>
            <p>
                2020 | Languages: C++
            </p>
        </div>
        <div class="index-box">
            <a href="#server" style="text-decoration:none;">Server Reservation Automation Script</a>
            <p>
                2017 | Languages: Python, Bash, HTML, CSS
            </p>
        </div>
        <div class="index-box">
            <a href="#performance" style="text-decoration:none;">Performance Analysis of Python Packages</a>
            <p>
                2017 | Languages: Python
            </p>
        </div>
    </div>
    <div style="width:70%;height:auto;display:block;float:right;margin-left:2%"> 
        <span class="anchor" id="lyricloud"></span>
            <div class="project-box"> 
                <div class="project-image">
                    <img src="/assets/lyricloud.png" class="collapsible-image" style="width:100%;max-width:300px;">
                </div>
                <h2>Lyricloud: Wordcloud Generator for Song Lyrics</h2>
                <div style="margin: 20px;">
                Built full end-to-end webservice using React.js for frontend deployment and Node Express for the backend server. Lyricloud scrapes music lyrics from Genius.com and converts them to a WordCloud format using the react-wordcloud module. The backend server performs the webscraping and text processing while the frontend calls the server's API to retrieve the relevant lyrics. WORK IN PROGRESS. To be implemented: smart searches, webscraping lyrics from backup websites, support for foreign languages, handling for songs with multiple artists, Wordcloud generation for multiple songs.
                </div>
                <div style="width:100%;">
                    <div style="text-align:center;">
                        <a href="https://lyricloud.netlify.app" style="text-decoration:none;text-align:center;">Lyricloud</a>
                    </div>
                    <h3>Technologies: React.js, Node Express, Node.js<br>
                    Languages: Javascript, HTML, CSS<br>
                    2021
                    </h3>
                </div>
            </div>
        <span class="anchor" id="cookies"></span>
        <div class="project-box"> 
            <div class="project-image">
                <img src="/assets/weed.png" class="collapsible-image" style="width:100%;max-width:300px;">
            </div>
            <h2>Cookies.co Sales Analysis and Prediction</h2>
            <div style="margin: 20px;">
            A comprehensive processing and analysis of various Cookies.co data sheets was conducted and then used to generate a model to predict future sales for any given brand of Cannabis. A few of the selected features included Brand, total sales, prior sales, rolling average sales, units sold, rolling average units sold, average retail price, variety (amount of cannabis categories a brand sells), and product count. Multiple models were then tested using R^2, MAE, MSE, RMSE and kfold cross validation for evaluation. The models tested included Linear regression with Lasso and Ridge, Linear regression with TruncatedSVD (dimensionality reduction), AdaBoost with TruncatedSVD, Regression Tree w/wo Truncated SVD and BaggingRegressor.
            </div>
            <div style="width:100%;">
                <h3>Technologies: Pandas, Numpy, sklearn, TruncatedSVD, K-fold Cross Validation, AdaBoost, GridSearchCV, Linear Regression, Regression Tree, BaggingRegressor, Ridge, Lasso<br>
                Languages: Python<br>
                2021
                </h3>
            </div>
        </div>
        <span class="anchor" id="nobel"></span>
        <div class="project-box"> 
            <div class="project-image">
                <img src="/assets/laureate.png" class="collapsible-image" style="width:100%;max-width:500px;">
            </div>
            <h2 >Nobel Laureate JSON Web-service API</h2>
            <div style="margin: 20px;">
            Data on Nobel Laureates was originally provided in JSON format which was then converted into MySQL load files for a relational schema designed from scratch. Data was then loaded into the appropriate tables in. Using PHP inside an Apache Web server, a web service was created for users to request Nobel Laureate data from. The PHP script regenerated the original JSON data for the user by querying the database and then printing on the website.
            </div>
            <div style="width:100%;">
                <h3>Technologies: Apache, MariaDB, JSON<br>
                Languages: PHP, SQL, Python<br>
                2021
                </h3>
            </div>
        </div>
        <span class="anchor" id="movie"></span>
        <div class="project-box"> 
            <div class="project-image">
                <img src="/assets/movie.png" class="collapsible-image" style="width:100%;max-width:200px;">
            </div>
            <h2 >Movie/Actor Database System</h2>
            <div style="margin: 20px;">
            A fully functional movie database system was created which was accessible to users through a website. The website was implemented using PHP running inside an Apache Web server with data managed by MySQL. Information about actors and movies are displayed (including info on associated movies/actors and ratings/comments) given an id from the request url. Additionally, there is a search page that allows one to search for either movie or actor within the database. Users can insert data into the database by submitting reviews and adding comments on the website.
            </div>
            <div style="width:100%;">
                <h3>Technologies: Apache, MariaDB<br>
                Languages: PHP, SQL<br>
                2021
                </h3>
            </div>
        </div>
        <span class="anchor" id="google"></span>
        <div class="project-box"> 
            <div class="project-image">
                <img src="/assets/serverherd.png" class="collapsible-image" style="width:100%;max-width:250px;">
            </div>
            <h2 >Google Places Application Server Herd</h2>
            <div style="margin: 20px;">
            5 servers were initialized with bidirectional communication channels utilizing asyncio. Each server accepts TCP connections from "mobile clients" which can share location data to the servers. Clients can also request the places nearby another client's most recent location using the Google Places API with an HTTP GET (using aiohttp). Client location data is propagated to each server and the server herd should continue to operate even in the event of one server shutting down. 
            </div>
            <div style="width:100%;">
                <h3>Technologies: Google Places API, Asyncio, Aiohttp<br>
                Languages: Python<br>
                2021
                </h3>
            </div>
        </div>
        <span class="anchor" id="simple"></span>
        <div class="project-box"> 
            <div class="project-image">
                <img src="/assets/router.png" class="collapsible-image" style="width:100%;max-width:250px;">
            </div>
            <h2 >Simple Router Implementation</h2>
            <div style="margin: 20px;">
            A simple router was created that would function similarly to a real router by receiving packets, processing them, and forwarding them to the correct interface via longest-prefix matching lookups in a routing table. The router ran on top of Mininet which allowed me to emulate a network topology on a single machine. The router was able to handle ethernet frames, IPv4 packets and ICMP packets and also verify packets via checksum/length while discarding invalid packets. 
            </div>
            <div style="width:100%;">
                <h3>Technologies: Vagrant, Mininet, ICMP, IPv4<br>
                Languages: C++<br>
                2021
                </h3>
            </div>
        </div>
        <span class="anchor" id="stock"></span>
        <div class="project-box"> 
            <div class="project-image">
                <img src="/assets/stock.png" class="collapsible-image" style="width:100%;max-width:175px;">
            </div>
            <h2 >Stock Price Prediction with CNN articles</h2>
            <div style="margin: 20px;">
            Used BeautifulSoup to parse CNN articles and count keywords. Given a specific date, the algorithm could count the most used keywords across all articles for the day. These wordcounts could then be used as features for a linear regression for calculating stock price. For example, the number of times "recession" is mentioned in a day could be of note. Combined with historic stock data from Yahoo Finance, these features were used in a linear regressor (sklearn) to estimate stock prices in the future for any given stock.
            </div>
            <div style="width:100%;">
                <h3>Technologies: BeautifulSoup, Sci-kit Learn, Matplotlib, Pandas<br>
                Languages: Python<br>
                2020
                </h3>
            </div>
        </div>
        <span class="anchor" id="delivery"></span>
        <div class="project-box"> 
            <div class="project-image">
                <img src="/assets/delivery.png" class="collapsible-image" style="width:100%;max-width:250px;">
            </div>
            <h2 >Delivery Navigation in LA</h2>
            <div style="margin: 20px;">
            LA Map data was loaded in via text files and then converted to usable coordinates and street segments. Routing was calculated from point to point using the A* search algorithm to minimize distance travelled. For inputs with multiple deliveries, simulated annealing (stochastic) was applied to optimize the order in which deliveries were made. Instructions for a driver were then generated with turn by turn navigation provided for them.
            </div>
            <div style="width:100%;">
                <h3>Technologies: Simulated Annealing, A* Search<br>
                Languages: C++<br>
                2020
                </h3>
            </div>
        </div>
        <span class="anchor" id="server"></span>
        <div class="project-box"> 
            <div class="project-image">
                <img src="/assets/intel.png" class="collapsible-image" style="width:100%;max-width:350px;">
            </div>
            <h2 >Server Reservation Automation Script</h2>
            <div style="margin: 20px;">
            A full end-to-end project was created to combat the issue of resource conflicts with Intel servers (especially important when measuring performance). A basic bash script was created to SSH to all the remote machines, record CPU specs and then report availability. This was integrated with multiple Python scripts that then dynamically generated a webpage hosted using Apache and Django which team members could easily access.
            </div>
            <h3>Technologies: Apache, Django, WSGI<br>
                Languages: Python, Bash, HTML, CSS<br>
                2017
            </h3>
        </div>
        <span class="anchor" id="performance"></span>
        <div class="project-box"> 
            <div class="project-image">
                <img src="/assets/performance.png" class="collapsible-image" style="width:100%;max-width:350px;">
            </div>
            <h2 >Performance Analysis of Python Packages</h2>
            <div style="margin: 20px;">
            A comprehensive performance analysis was conducted of multiple scientific Python packages (Numpy, Nengo, Astropy, Sympy) using available open source benchmark suites. Tools used include Air Speed Velocity (ASV) which benchmarks python projects over their lifetime, Cprofile which counts CPU cycles and where they're used, Perf which also displays cycle usage and distribution, and Top which allowed me to measure CPU utilization. The Python Benchmark Suite was another more comprehensive benchmark that was tested. Comparisons were drawn between the performance of the default Cpython and the PyPy Interpreter which my team at Intel was currently studying.
            </div>
            <h3>Technologies: AirSpeedVelocity, Perf, Cprofile, PyPy
                Interpreter<br>
                Languages: Python<br>
                2017
            </h3>
        </div>
    </div>
</div>
<div style="height:100px">
</div>


