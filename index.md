---
title: Malyaban Bal
feature_text: 
---
Passionate Brain-inspired ML Researcher, Engineer, Reader...

<blockquote cite="http://www.imdb.com/title/tt0284978/quotes/qt1375101">
  <p>You planning a vacation, Mr. Sullivan?</p>
  <footer>
    <a href="http://www.imdb.com/title/tt0284978/quotes/qt1375101">Sunways Security Guard</a>
  </footer>
</blockquote>


<style>
blockquote {
  text-align: left;
  font-weight: bold;
}
blockquote footer {
  font-size: .8rem;
}
</style>

<script>
const blockquote = document.querySelector("blockquote")
const bolden = (keyString, string) =>
  string.replace(new RegExp(keyString, 'g'), '<strong>'+keyString+'</strong>')

blockquote.innerHTML = bolden("Mr. Sullivan", blockquote.innerHTML)
</script>

