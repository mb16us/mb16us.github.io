# mb16.us

## home page for mb16.us
[original site](https://www.mb16.us/)

___


[Michelle and Bryce](https://photos.app.goo.gl/yiyf9Mra3Lei3PvR7)

___


[The Dogs](https://photos.app.goo.gl/dpS1mSaTQweeLCdM6)

___


<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
