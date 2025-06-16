---
pageClass: home-page
# some data for the components

name: Shridhar Vashishtha
profile: /profile.jpg

bio: First year Computer Science PhD student @ The University of Utah
email: shridhar.vashishtha [ AT ] utah.edu
---

<ProfileSection :frontmatter="$page.frontmatter" />

## About Me

I am a first year computing PhD student at the Kahlert School of Computing & Scientific Computing and Imaging Institute at the University of Utah. I am supervised by [Dr. Mike Kirby](https://users.cs.utah.edu/~kirby/) and [Dr. Shandian Zhe](https://users.cs.utah.edu/~zhe/). 
I am broadly interested in scientific machine learning, physics-informed machine learning, probabilistic machine learning, and theoretical foundations of machine learning. 
I completed my undergraduate degree in computer science from the University of Minnesota-Twin Cities under the supervision of [Dr. Vipin Kumar](https://www-users.cse.umn.edu/~kumar001/). My honors thesis was titled "[Deep Learning to Address Data Sparsity in Climate Change Monitoring](https://conservancy.umn.edu/items/194f096b-8dd4-4a88-94f2-60d13ad5c482)".

<p style="font-size:17px; padding-top:0.75em ">Short Bio</p>

- PhD student at the Kahlert School of Computing and Scientific Computing and Imaging Institute, <span style="color:FireBrick; ">The University of Utah</span>, Salt Lake City <br/>
<span style="color:Gray; ">May 2025 - *present*</span>

- BS in Computer Science (Minor in Mathematics) <span style="color:FireBrick; ">University of Minnesota-Twin Cities</span>, Minneapolis <br/>
<span style="color:Gray; ">2021 - 2025</span>

## Papers

- More coming "soon".

<!-- Custom style for this page -->

<style lang="stylus">

.theme-container.home-page .page
  font-size 15px
  font-family "lucida grande", "lucida sans unicode", lucida, "Helvetica Neue", Helvetica, Arial, sans-serif;
  p
    margin 0 0 0.5rem
  p, ul, ol
    line-height normal
  a
    font-weight normal
  .theme-default-content:not(.custom) > h2
    margin-bottom 0.5rem
  .theme-default-content:not(.custom) > h2:first-child + p
    margin-top 0.5rem
  .theme-default-content:not(.custom) > h3
    padding-top 4rem

  /* Override */
  .md-card
    margin-top 0.5em
    .card-image
      padding 0.2rem
    .card-content p
      -webkit-margin-after 0.2em

@media (max-width: 419px)
  .theme-container.home-page .page
    p, ul, ol
      line-height 1.5

    .md-card
      .card-image
        img 
          width 100%
          max-width 400px

</style>
<p style="font-size: 13px; text-align: center; color: gray; padding-top: 2em;">
  Adapted from <a href="https://github.com/dvtailor/dvtailor.github.io" target="_blank" rel="noopener noreferrer">Dharmesh Tailor's fork</a> of <a href="https://github.com/leonidk/leonidk.github.io" target="_blank" rel="noopener noreferrer">Leonid Keselman's website</a>.
</p>