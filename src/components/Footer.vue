<template>
  <footer class="footer">
    <!-- Upper Footer -->
    <div class="footerContainer centered">
      <div class="content">
        <div class="columns">
          <div
            class="column"
            title="VAI Beacon Network website internal navigation"
          >
            <p class="footer-heading">VAI Beacon Network</p>
            <ul>
              <li>
                <router-link
                  to="/guide"
                  title="A guide on how to user the Beacon Network user interface"
                  >How to use Beacon Network</router-link
                >
              </li>
              <li>
                <router-link
                  to="/join"
                  title="How to register a new Beacon to VAI Beacon Network"
                  >Join the Network</router-link
                >
              </li>
              <li>
                <router-link
                  to="/docs"
                  title="Technical documentation for web and API developers"
                  >For Developers</router-link
                >
              </li>
              <li>
                <router-link
                  to="/docsapi"
                  title="Technical documentation of advanced API usage"
                  >API Documentation</router-link
                >
              </li>
              <li>
                <router-link to="/accessibility" title="Accessibility statement"
                  >Accessibility Statement</router-link
                >
              </li>
            </ul>
          </div>
          <div class="column" title="Affiliated external links">
            <p class="footer-heading">More About Beacon</p>
            <ul>
              <li>
                <a
                  href="https://beacon-project.io/"
                  title="Information regarding the GA4GH/VAI Beacon project"
                  >Beacon Project</a
                >
              </li>
              <li>
                <a
                  href="https://elixir-europe.org/"
                  title="VAI Europe website"
                  >VAI Europe</a
                >
              </li>
              <li>
                <a href="https://www.ga4gh.org/" title="GA4GH website">GA4GH</a>
              </li>
              <li>
                <a
                  href="https://ga4gh-discovery.github.io/"
                  title="Information regarding the GA4GH/VAI Beacon Network project"
                  >GA4GH Discovery</a
                >
              </li>
            </ul>
          </div>
          <div class="column is-one-fifth">
            <a
              class="login"
              href="https://elixir-europe.org/"
              title="Go to VAI Europe"
              ><img
                src="@/assets/VAI-logo-2line-19_2C-new-web.png"
                alt="VAI Europe Logo"
            /></a>
          </div>
        </div>
      </div>
    </div>
    <!-- Lower Footer -->
    <div class="footerContainer">
      <div class="content">
        <div class="columns">
          <div class="column">
            <p></p>
          </div>
          <div class="column contact">
            <p class="address">
              VAI Beacon Network is operated by
              <a
                href="http://www.vai.org/"
                title="Go to VAI Europe"
                >VAI</a
              >
              |
              <a
                href="mailto:contact@vai.org"
                title="Contact the VAI Beacon Network operator"
                >contact@vai.org</a
              >
              <br />
              VAI Beacon Network is provided by
              <a
                href="http://www.vai.org"
                title="Go to VAI, the Beacon Network provider"
                >VAI</a
              >
              |
              <a
                href="https://www.csc.fi/"
                title="Go to VAI, the VAI Beacon Network provider"
                >VAI</a
              >
            </p>
            <p class="legal">
              Copyright © VAI 2021 |
              <router-link
                to="/tos"
                title="Read the Terms of Service of VAI Beacon Network"
                >Terms of Service</router-link
              >
              |
              <router-link
                to="/privacy"
                title="Read the Privacy Policy of VAI Beacon Network"
                >Privacy Policy</router-link
              >
            </p>
          </div>
        </div>
      </div>
    </div>
  </footer>
</template>

<script>
export default {
  name: "footer-bar"
};
</script>

<style lang="scss" scoped>
.footer {
  background: #3e3e3e;
  color: white;
  padding: 0;
  flex-shrink: 0;
  font-size: 0.875em;
  margin-top: 20px;
}
.footer .footerContainer.centered h5 {
  color: white;
  padding-bottom: 5px;
  border-bottom: solid 1px white;
  width: 50%;
  min-width: 300px;
}
.footer .footerContainer.centered ul {
  margin: 0;
  padding: 0;
}
.footer .footerContainer.centered ul li {
  list-style-type: none;
  margin: 0;
  padding: 0;
}
.footer .footerContainer.centered ul li a {
  color: white;
}
.footer .footerContainer.centered ul li a:hover {
  color: #f47d21;
}
.footer a {
  color: #0bf;
}
.footer a:hover {
  color: #f47d21;
}
.footer .footerContainer.centered {
  padding: 2rem 0;
  max-width: 1200px;
  margin: 0 auto;
}
.footer .footerContainer.centered .is-one-fifth {
  text-align: center;
}
.footer .footerContainer + .footerContainer {
  background: #023452;
  padding-left: 3rem;
  padding-right: 3rem;
}
.footer .footerContainer + .footerContainer .content {
  max-width: 1200px;
  margin: 0 auto;
}
.footerContainer .contact {
  text-align: right;
}
.footerContainer .contact p {
  margin: 0;
}
.flag {
  height: 30px;
  float: left;
  margin: 5px 10px 0 0;
}
.footer-heading {
  color: #fff;
  border-bottom: solid 1px #fff;
  font-weight: 700;
  font-size: 16px;
}
</style>
