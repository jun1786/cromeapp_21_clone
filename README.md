var     let의 초기버전
 const  수정불가능(constant내의 object는 수정가능)
 let    수정가능

states(booleans)
 true       옳은
 false      틀린
 null       없는
 undefined  정의되지않은

arrays
 const array_name = []
 log(array_name[])
 array_name.push()

objects
 const object_name = {
     a: ,
     b: ,
 }

functions
 function function_name(arguments) {
 }

functions in object
 const object_name = {
     function_name : function(){
     }
 }

prompt(사용X)
 const prompt_name = prompt("string")
    --css 적용 불가능, 나머지 js 지연, 팝업 제한되기도--

parseInt(type exchange(string to number))

conditionals
 if(condition) {
    //condition === true
    action 
 }
 else {
     //condition === false
     action
 }

&& and ||
 ture && true   === true
 true && false  === false
 false && true  === false
 false && false === false
 true || true   === true
  true || false === true
 false || true  === true
 false || false === false

document
 head, title, body 호출 가능

window

getElementBy("")

querySelector(css처럼 사용 가능)
 querySelector(".class_name h1")
 querySelectorAll

events
 종류: console.dir에서 on으로 시작하는 event

.addEventListener("event", action_function)
.onevent = action_funtion

className
classList

contain
add/remove

toggle
 on/off 처리가 가능한 스위치
 add/remove 를 한번에

