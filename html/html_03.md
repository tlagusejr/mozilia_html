<h1> 리스트 만들기</h1>
<p> 페이지를 만들 때 h와 p로만 꾸민다면 엄청 심심하게 느껴질겁니다. 글자에 색을 넣거나 이미지, 동영상, 리스트, 테이블 등 여러가지 요소들을 삽입하여 더 시각적이게 보일 필요가 있을것 같아요.
 그 중에서 리스트를 먼저 할 생각입니다.</p>
<p> 리스트 처럼 보이게 하려면 &lt;p&gt;
<p>&lt;p&gt;01&lt;/p&gt;</p>
<p>&lt;p&gt;02&lt;/p&gt;</p>
<p>&lt;p&gt;03&lt;/p&gt;</p>
<p>이런 식으로도 나타낼수도 있겠죠. 그렇지만 list 태그를 사용하면 직관적이고 편하게 나타낼 수 있습니다. 그 중에서 &lt;ul&gt;(Unordered list) 리스트 태그를 사용하려면</p>

<p>&lt;ul&gt;</p>
<p>milk</p>
<p>eggs</p>
<p>bread</p
<p>hummus</p
<p>&lt;/ul&gt;</p>
식으로 태그를 만든다면 가능합니다.
<ul>
milk
eggs
bread
hummus
</ul>

<p>그렇지만 리스트가 한줄로 나타나는 것을 볼 수 있어요. 리스트 내부 항목이 필요하기 때문에 &lt;li&gt; 태그를 사용해야 합니다.</p><ul>
<p>&lt;ul&gt;&lt;/li&gt;</p>
<p>&lt;li&gt;milk&lt;/li&gt;</p>
<p>&lt;li&gt;eggs&lt;/li&gt;</p>
 <p>&lt;li&gt;bread&lt;/li&gt;</p>
<p>&lt;li&gt;hummus&lt;/li&gt;</p
<p>&lt;/ul&gt;</p>
 <p>를 사용하면</p>
 <ul>
<li>milk</li>
<li>eggs</li>
<li>bread</li>
<li>hummus</li>
</ul>
 <P>만약 순서가 있는 리스트(ordered)를 사용한다면<p>
 <p>&lt;ol&gt;&lt;/li&gt;</p>
<p>&lt;li&gt;milk&lt;/li&gt;</p>
<p>&lt;li&gt;eggs&lt;/li&gt;</p>
 <p>&lt;li&gt;bread&lt;/li&gt;</p>
<p>&lt;li&gt;hummus&lt;/li&gt;</p
<p>&lt;/ol&gt;</p>
 <ol>
<li>milk</li>
<li>eggs</li>
<li>bread</li>
<li>hummus</li>
</ol>
<p>간단하게 변경 가능하네요. </p>
다음은 강조를 알아보겠습니다.
