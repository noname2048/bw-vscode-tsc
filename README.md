# bw-vscode-tsc

vscode 에서 yarn3을 사용했을 때 타입스크립트를 인식하지 못해때 관련해서 알아보기

https://offbyone.tistory.com/444

결국 `yarn create react-app my-app --template typescript` 까지 실행하고 `yarn dlx @yarnpkg/sdks vscode` 를 한 뒤, vscode 내에서 workspace typescript version 까지 골라줬지만, 달라지는건 없었다. 이에 webstorm 을 써보기로 결정했다.

확실하진 않지만 지원을 안하는 것 같다는 이야기가 있다. https://reyoucat.tistory.com/m/113

yarn 3.0.2를 쓰는 누군가의 깃헙에서 클론했는데 express에 빨간줄을 긋지는 않았다. https://elvanov.com/2664 (리액트를 새로 설치했는데 그엇다. 이건 리액트 문제인가?)

이것까지는 진행해봐야겠다. https://kasterra.github.io/setting-yarn-berry/
typescript 와 react와 @types/react가 있는것 을 확인했다.
zipfs도 설치했는데 결국 작동하진 않았다.
