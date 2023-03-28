# CSS 정리
## 문서 스타일링 방법
1. ```<TAG style="">```
2. ```<style>...</style>```
3. .css 파일 만들어서 link

## 형식
```
selector{
    arrtibute: value /* daclarait */

}
```

### selector
<pre>
*       모든 태그 다 적용
TMG     특정 태그 적용
#id     유일한 id에 적용
.class  같은 class에 적용

selector1 > seletor2    seletor1의 자식 seletor2에 적용
selector1  seletor2     seletor1의 자손 seletor2에 적용
selector1, seletor2     seletor1과 seletor2에 같이 적용(중요)
selector1 + seletor2    
selector1 ~ seletor2


seletor:first-child()   
seletor:nth-child(n)
seletor:last-child()

seletor:hover       마우스 올렸을 때의 seletor

[속성="값"]         <...속성="값">에 적용
</pre>

# 우선순위
1.
2.
3.#id
4. .class
5. TAG
6. *
- 구채 > 포괄
- 같은 우선순위일 떄, 나중에 쓴 게 적용                                                                                           
