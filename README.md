
<h1>Auto views</h1>

<br/>

- 셀레니움을 활용하여 유튜브의 조회수를 늘려주는 매크로입니다.
- 화살표키를 통한 5초스킵기능을 응용해 영상을 지속적으로 스킵하면서 고속으로 조회수를 증가시킵니다.

<br/>

```python
from autoviews import AutoViews

av = AutoViews()
av.playVideo("https://www.youtube.com/watch?v=jsFhMMxximg")
```

<br/>

- 초반 크롬창이 뜨고 유튜브 사이트에 로딩하는데까지 걸리는 시간을 감안해 작동되는 딜레이를 설정할 수 있습니다.
- 또한, 5초스킵하는 속도도 설정할 수 있습니다.

<br/>

```python
from autoviews import AutoViews

#skip_delay : youtube viewo 5 seconds skip delay. (0.1 -> 0.1 second)
#delay : wait delay for loading. (4 -> 4 seconds)

av = AutoViews()
av.playVideo("https://www.youtube.com/watch?v=jsFhMMxximg", skip_delay=0.1, delay=4)
```

<br/>

<h3>위의 예제를 실행시켜보면 작동하는 방식과 인자값들을 어떻게 넣어야하는지 이해가 갈 것입니다. Just do it.</h3>
