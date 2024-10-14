# 골프존 R&D센터 안드로이드 과제

API를 결과인 이미지 리스트를 사용하여 다음 요구사항에 맞춰 안드로이드 앱을 작성해주세요

```
1. 프로젝트는 멀티모듈을 필수적으로 구성해주세요 (App module 외 최소 1개 이상)

2. UI는 fragment 2개를 사용합니다.

3. Bottom Tab을 하용하여 fragment를 전환합니다.

4. 첫번째 fragment (LIST)
  * 이미지 목록을 Grid (column 3) 형태로 보여줍니다.
  * 스크롤을 통해 다음 페이지의 이미지를 불러옵니다. (최대한 자연스러운 스크롤이 될수 있도록 해주세요)
  * 하나의 이미지는 정사각형으로 노출합니다. (이미지는 CenterCrop)
  * 이미지 위에 다음을 표시하세요
    - 이미지 ID (API에서 받은 id)
    - Favorite 추가된 이미지는 추가되었다는 아이콘을 보여줍니다.(좋아요/별표/하트 등)
  * 이미지를 선택(터치)하면 Favorite에 추가합니다.
  * 이미 추가된 이미지를 다시 선택(터치)하는 경우에는 Favorite에서 제거합니다.

5. 두번쩨 fragment (FAVORITE)
  * Favorite에 추가된 이미지 목록을 화면에 보여주세요
  * 요구사항은 첫번째 fragment와 같습니다.
  * Favorite에 추가된 내용은 앱 재시작 후에도 보여야 합니다.
    (Room, DataStore, SharedPreferences 등을 선택적으로 이용)

6. API는 (https://thedogapi.com/)에서 Free plan으로 apikey를 발급받아서 적용해주세요

7. 다음 키워드를 참고 하여 프로젝트를 구성해 주세요
   (모든 요소가 필수는 아닙니다.)
  * MVVM
  * Flow
  * Coroutine
  * Retrofit2
  * Glide4
  * Paging3
```

추가 개발 요구 사항

```
1. gridItem을 long click하는 경우 상세 페이지로 이동합니다. (새로운 Activity)
2. 선택된 이미지를 보여줍니다.
3. API에서 받은 정보를 왼쪽, 아래에 표시해 주십니다.
4. 오른쪽 상단에 favorite icon을 노출해주세요 (선택된 것과 선택되지 않은것 구분)
5. favorite icon를 터치하면 하면 favorite에 추가 및 제거가 되어야 합니다.
6. 이미지는 스와이프하여 이전 이미지와 이후 이미지로 이동합니다.
7. paging이 필요한 경우 api를 통해 다음 페이지를 요청해주세요
```

