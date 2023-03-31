# OTTAppIntro

## OTT App Intro 구현해보기

Motion Layout을 사용하여 구현해보았다.

## 배운것들

 * statusbar & navigation 화면 확장
   * activity window 에서 setFlags 를 통해 가능
   
 * 스크롤 위치에 따른 애니메이션

    * viewTreeObserver 통해 스크롤시 height 값을 받아와 그 값에 따라 애니메이션 가능

  * 2차애니메이션
  
    * TransitionListener 를 통해 onTransitionCompleted 사용하여 2차 애니매이션 사용


저렇게 할경우 컨텐츠가 statusbar와 navigation
## issue
* setFlags(WindowManager.LayoutParams.FLAG_LAYOUT_NO_LIMITS) 로 확장시킬시
컨텐츠가 statusBar & navigationbar 가림현상 발생

inset을 통해 padding 처리 


  
  
  
