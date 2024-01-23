# 카카오 지도

- 페이지/라우터/컴포넌트 구성

## 1. page / 레이아웃

- /src/pages/map/MapPage.js

```js
// 코드 생략
```

## 2. 기능 컴포넌트

- /src/components/map/MapComponent.js

```js
import React from "react";

const MapComponent = () => {
  return <div>MapComponent</div>;
};

export default MapComponent;
```

## 3. 페이지에 컴포넌트 배치하기

```js
import React from "react";
import BasicLayout from "../../layouts/BasicLayout";
import MapComponent from "../../components/map/MapComponent";

const MapPage = () => {
  return (
    <BasicLayout>
      <h1>카카오 지도</h1>
      <MapComponent />
    </BasicLayout>
  );
};

export default MapPage;
```
