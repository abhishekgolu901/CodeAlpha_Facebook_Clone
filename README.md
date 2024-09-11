<!DOCTYPE html>
<html>
<head>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Facebook Clone</title>
    <link rel="stylesheet" href="style.css">
    <script src="https://kit.fontawesome.com/c4254e24a8.js" crossorigin="anonymous"></script>
</head>
<body>
    
    <nav>
        <div class="nav-left">
          <a href="index.html"><img src="images/logo3.png" class="logo"></a>
        <ul>
           
            <li><img src="images/notification.png"></li>
            <li><img src="images/inbox.png"></li>
            <li><img src="images/video.png"></li>
        </ul>
        </div>
        
        <div class="nav-right">
            <div class="search-box">
                <img src="images/search.png">
                <input type="text" placeholder="Search">
            </div>
            <div class="nav-user-icon online" onclick="settingsMenuToggle()">
                <img src="images/profile-pic1.jpg">
            </div>
            
        </div>
        <!-- ------dropdown-settings-menu--------- -->
        <div class="settings-menu">
            <div id="dark-btn">
                <span></span>
            </div>
            <div class="settings-menu-inner">
                <div class="user-profile">
                    <img src="images/profile-pic1.jpg">
                    <div>
                        <p>Abhishek kumar</p>
                        <a href="profile.html">See your profile</a>
                    </div>
                </div>
                <hr>
                <div class="user-profile">
                    <img src="images/feedback.png">
                    <div>
                        <p>Give Feedback</p>
                        <a href="">Help us improve the new deisgn</a>
                    </div>
                </div>
                <hr>
                <div class="settings-links">
                    <img src="images/setting.png" class="settings-icon">
                    <a href="">Settings & Privacy <img src="images/arrow.png" width="10px"></a>
                </div>
                <div class="settings-links">
                    <img src="images/help.png" class="settings-icon">
                    <a href="">Help & Support <img src="images/arrow.png" width="10px"></a>
                </div>
                <div class="settings-links">
                    <img src="images/display.png" class="settings-icon">
                    <a href="">Display & Accessibility <img src="images/arrow.png" width="10px"></a>
                </div>
                <div class="settings-links">
                    <img src="images/logout.png" class="settings-icon">
                    <a href="">Logout <img src="images/arrow.png" width="10px"></a>
                </div>
            </div>
            
        </div>
    </nav>
    <div class="container">
       <div class="left-sidebar">
           <div class="imp-links">
               <a href="#"><img src="images/news.png"> Latest News</a>
               <a href="#"><img src="images/friends.png"> Friends</a>
               <a href="#"><img src="images/group.png"> Groups</a>
               <a href="#"><img src="images/marketplace.png"> Marketplace</a>
               <a href="#"><img src="images/watch.png"> Watch</a>
               <a href="#">See More</a>
           </div>
           <div class="shortcut-links">
            <p>Your Shortcuts</p>
            <a href="#"><img src="images/shortcut-1.png"> Web Developers</a>
            <a href="#"><img src="images/shortcut-2.png"> Web Design Course</a>
            <a href="#"><img src="images/shortcut-3.png"> Full Stack Development</a>
            <a href="#"><img src="images/shortcut-4.png"> Website Experts</a>
            
        </div>
       </div>
<!----------------- middle content--------- -->
       <div class="main-content">
        <div class="story-gallery">
            <div class="story story1">
                <img src="images/profile-pic1.jpg">
                <p>Post Story</p>
            </div>
            <div class="story story2">
                <img src="images/member-2.jpg">
                <p>Rahul Kumar Sah</p>
            </div>
            <div class="story story3">
                <img src="images/member-1.jpg">
                <p>Vivek Kumar Raj</p>
            </div>
            <div class="story story4">
                <img src="images/member-8.jpg">
                <p>Abhishek Gupta Abhi</p>
            </div>
            <div class="story story5">
                <img src="images/member-7.jpg">
                <p>Amit Kumar</p>
            </div>
        </div>

        <div class="write-post-container">
            <div class="user-profile">
                <img src="images/profile-pic1.jpg">
                <div>
                    <p>Abhishek Kumar</p>
                    <small>Public <i class="fas fa-caret-down"></i></small>
                </div>
            </div>

            <div class="post-input-container">
                <textarea rows="3" placeholder="What's on your mind?"></textarea>
                <div class="add-post-links">
                    <a href="#"><img src="images/live-video.png"> Live Video</a>
                    <a href="#"><img src="images/photo.png"> Photo/Video</a>
                    <a href="#"><img src="images/feeling.png"> Feeling/Activity</a>
                </div>
            </div>

        </div>
        <div class="post-container">
            <div class="post-row">
                <div class="user-profile">
                    <img src="images/profile-pic1.jpg">
                    <div>
                        <p>Abhishek Kumar</p>
                        <span>Sept 09 2024, 03:29 pm</span>
                    </div>
                </div>
                <a href="#"><i class="fas fa-ellipsis-v"></i></a>
            </div>
            <p class="post-text">“In the darkest night, stars still gleam, Hope shines bright, like a timeless dream. Believe in yourself, for you are supreme”</a></p>
            <img src="images/feed-image-1.jpg" class="post-img">
            <div class="post-row">
                <div class="activity-icons">
                    <div><img src="images/like-blue.png"> 120</div>
                    <div><img src="images/comments.png"> 45</div>
                    <div><img src="images/share.png"> 20</div>
                </div>
                <div class="post-profile-icon">
                    <img src="images/profile-pic1.jpg"> <i class="fas fa-caret-down"></i>
                </div>
            </div>

        </div>

        <div class="post-container">
            <div class="post-row">
                <div class="user-profile">
                    <img src="images/profile-pic1.jpg">
                    <div>
                        <p>Abhishek Kumar</p>
                        <span>Aug 25 2024, 02:19 pm</span>
                    </div>
                </div>
                <a href="#"><i class="fas fa-ellipsis-v"></i></a>
            </div>
            <p class="post-text">Kisi Ki Yaad Mein Itna Udaas Na Huwa kar, Log Naseeb Sy Milty Hain Udaasiyon Sy Nhi.</a></p>
            <img src="images/feed-image-2.jpg" class="post-img">
            <div class="post-row">
                <div class="activity-icons">
                    <div><img src="images/like.png"> 120</div>
                    <div><img src="images/comments.png"> 45</div>
                    <div><img src="images/share.png"> 20</div>
                </div>
                <div class="post-profile-icon">
                    <img src="images/profile-pic1.jpg"> <i class="fas fa-caret-down"></i>
                </div>
            </div>

        </div>

        <div class="post-container">
            <div class="post-row">
                <div class="user-profile">
                    <img src="images/profile-pic1.jpg">
                    <div>
                        <p>Abhishek Kumar</p>
                        <span>Aug 22 2024, 09:40 am</span>
                    </div>
                </div>
                <a href="#"><i class="fas fa-ellipsis-v"></i></a>
            </div>
            <p class="post-text">Do Chehry Insaan Kabhi Nhi Bhulata Hai, Ek Mushkil Mein Saath Deny Waala, Dusra Mushkil Mein Saath Chodny Waala.</a></p>
            <img src="images/feed-image-3.jpg" class="post-img">
            <div class="post-row">
                <div class="activity-icons">
                    <div><img src="images/like.png"> 120</div>
                    <div><img src="images/comments.png"> 45</div>
                    <div><img src="images/share.png"> 20</div>
                </div>
                <div class="post-profile-icon">
                    <img src="images/profile-pic1.jpg"> <i class="fas fa-caret-down"></i>
                </div>
            </div>

        </div>

        <div class="post-container">
            <div class="post-row">
                <div class="user-profile">
                    <img src="images/profile-pic1.jpg">
                    <div>
                        <p>Abhishek Kumar</p>
                        <span>Aug 20 2024, 01:49 pm</span>
                    </div>
                </div>
                <a href="#"><i class="fas fa-ellipsis-v"></i></a>
            </div>
            <p class="post-text">Sachi Mohabat Kabhi Khatam Nhi Hoti, Bas Waqt Ky Saath Khamoosh Ho Jati Hai.</a></p>
            <img src="images/feed-image-4.jpg" class="post-img">
            <div class="post-row">
                <div class="activity-icons">
                    <div><img src="images/like.png"> 120</div>
                    <div><img src="images/comments.png"> 45</div>
                    <div><img src="images/share.png"> 20</div>
                </div>
                <div class="post-profile-icon">
                    <img src="images/profile-pic1.jpg"> <i class="fas fa-caret-down"></i>
                </div>
            </div>

        </div>

        <div class="post-container">
            <div class="post-row">
                <div class="user-profile">
                    <img src="images/profile-pic1.jpg">
                    <div>
                        <p>Abhishek Kumar</p>
                        <span>Aug 20 2024, 08:17 am</span>
                    </div>
                </div>
                <a href="#"><i class="fas fa-ellipsis-v"></i></a>
            </div>
            <p class="post-text">Zindagi ko kya Zarurt ha manzilo ki, Waqt har manzil aasan bna deta ha, Marta nhi kissi se judaa ho kr koi, Yeh waqt use bhi jina sikha deta ha.</a></p>
            <img src="images/feed-image-5.jpg" class="post-img">
            <div class="post-row">
                <div class="activity-icons">
                    <div><img src="images/like.png"> 120</div>
                    <div><img src="images/comments.png"> 45</div>
                    <div><img src="images/share.png"> 20</div>
                </div>
                <div class="post-profile-icon">
                    <img src="images/profile-pic1.jpg"> <i class="fas fa-caret-down"></i>
                </div>
            </div>

        </div>
        
        <button type="button" class="load-more-btn">Load More</button>

       </div>
<!-- ----------right sidebar----------- -->
       <div class="right-sidebar">
           <div class="sidebar-title">
               <h4>Events</h4>
               <a href="#">See All</a>
           </div>

           <div class="event">
               <div class="event-left">
                    <h3>15</h3>
                    <span>April</span>
               </div>
               <div class="event-right">
                   <h4>Social Media</h4>
                   <p><i class="fas fa-map-marker-alt"></i> Willson Tech Park</p>
                   <a href="#">More Info</a>
               </div>
           </div>
           <div class="event">
            <div class="event-left">
                 <h3>23</h3>
                 <span>April</span>
            </div>
            <div class="event-right">
                <h4>Mobile Marketing</h4>
                <p><i class="fas fa-map-marker-alt"></i> Willson Tech Park</p>
                <a href="#">More Info</a>
            </div>
        </div>

        <div class="sidebar-title">
            <h4>Advertisement</h4>
            <a href="#">Close</a>
        </div>

        <img src="images/advertisement.jpg" class="sidebar-ad">

        <div class="sidebar-title">
            <h4>Conversation</h4>
            <a href="#">Hide Chat</a>
        </div>

        <div class="online-list">
            <div class="online"><img src="images/member-7.jpg"></div>
            <p>Amit Kumar</p>
        </div>
        <div class="online-list">
            <div class="online"><img src="images/member-9.jpg"></div>
            <p>Vijay Kumar Sah</p>
        </div>
        <div class="online-list">
            <div class="online"><img src="images/member-6.jpg"></div>
            <p>Anita Kumari</p>
        </div>
        

       </div>
    </div>
    <div class="footer">
        <p>Privacy  · Terms  · Advertising  · Ad choices   · Cookies  ·   Meta © 2024</p>
    </div>

    <script src="script.js"></script>
</body>
</html>
