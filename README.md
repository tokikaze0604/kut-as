# kut-as(KUT-ArtShow)

- ここでホームページを作っていきます。
- centos6.5
-  入れたもの
  + npm
  + vim
  + httpd

  <nav>
          <h1>Cafe de Rome</h1>
          <div id="menu">
            <p>俺はここにいるぞ!</p>
            <ul>
              <li>Home</li>
              <li>News</li>
              <li>Comcept</li>
              <li>Access</li>
            </ul>
          </div>
        </nav>


///////////////css///////////////////////////

nav {
  display: block;
  margin: 0 auto;
  height: 65px;
}

nav h1 {
  display: inline-block;
  float: left;
  margin-bottom: 0px;
}

#menu {
  display: block;
  float: left;
}

#menu p {
  text-align: center;
  font-size: 5px;
}

#menu p, ul, li {
  margin-bottom: 0px;
}

#menu ul {
  list-style-type: none;
  display: inline-block;
}

#menu li {
  display: inline-block;
  border-left: 1px #000000 solid;
  border-right: 1px #000000 solid;
  margin-left: 3px;
  margin-right: 3px;
  padding-left: 2px;
  padding-right: 2px;
}

#top_img {
  clear: both;
}
