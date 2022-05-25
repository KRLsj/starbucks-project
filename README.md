# ☕ STARBUCKS☕

### < 스타벅스 홈페이지 클론 코딩>

**작업기간** : 2022. 05. 01 ~ 2022. 05. 21

**참여인원** : 1인 (개인 프로젝트) 

<br>

**스킬 및 사용 툴**

![HTML5](https://img.shields.io/badge/HTML5-%23E34F26.svg?style=flat-square&logo=html5&logoColor=white&max-width=100%)
![CSS3](https://img.shields.io/badge/CSS3-%231572B6.svg?style=flat-square&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-%23323330.svg?style=flat-square&logo=javascript&logoColor=%23F7DF1E)
![Netlify](https://img.shields.io/badge/Netlify-%23000000.svg?style=flat-square&logo=netlify&logoColor=#00C7B7)
![Git](https://img.shields.io/badge/Git-%23F05033.svg?style=flat-square&logo=git&logoColor=white)
``

## Main menu in Header

```html
<ul class="main-menu">
        <li class="item">
          <div class="item__name">COFFEE</div>
          <div class="item__contents">
            <div class="contents__menu">
              <ul class="inner">
                <li>
                  <h4>커피</h4>
                  <ul>
                    <li>스타벅스 원두</li>
                    <li>스타벅스 비아</li>
                    <li>스타벅스앳홈 by 캡슐</li>
                  </ul>
                </li>
                <li>
                  <h4>나와 어울리는 커피</h4>
                  <ul>
                    <li></li>
                  </ul>
                </li>
                <li>
                  <h4>스타벅스 리저브TMI</h4>
                  <ul>
                    <li>RESERVE MAGAZINE</li>
                  </ul>
                </li>
                <li>
                  <h4>에스프레소 음료</h4>
                  <ul>
                    <li>도피오</li>
                    <li>에스프레소 마키아또</li>
                    <li>아메리카노</li>
                    <li>마키아또</li>
                    <li>카푸치노</li>
                    <li>라떼</li>
                    <li>모카</li>
                  </ul>
                </li>
                <li>
                  <h4>최상의 커피를 즐기는 법</h4> 
                  <ul>
                    <li>커피 프레스</li>
                    <li>푸어 오버</li>
                    <li>아이스 푸어 오버</li>
                    <li>커피 메이커</li>
                    <li>리저브를 매장에서 다양하게 즐기는 법</li>
                  </ul>
                </li>
                <li>
                  <h4>커피 이야기</h4>
                  <ul>
                    <li>농장에서 우리의 손으로</li>   
                    <li>최상의 아라비카 원두</li>
                    <li>스타벅스 로스트 스팩트럼</li>
                    <li>스타벅스 디카페인</li>
                    <li>클로버® 커피 추출 시스템</li>
                  </ul>
                </li>
              </ul>
            </div>
            <div class="contents__texture">
              <div class="inner">
                <h4>나와 어울리는 커피 찾기</h4>
                <p>스타벅스가 여러분에게 어울리는 커피를 찾아드립니다.</p>
                <h4>최상의 커피를 즐기는 법</h4>
                <p>여러가지 방법을 통해 다양한 풍미의 커피를 즐겨보세요.</p>
              </div>
            </div>
          </div>
        </li>
        <li class="item">
          <div class="item__name">MENU</div>
          <div class="item__contents">
            <div class="contents__menu">
              <ul class="inner">
                <li>
                  <h4>음료</h4>
                  <ul>
                    <li>콜드 브루</li>
                    <li>브루드 커피</li>
                    <li>에스프레소</li>
                    <li>프라푸치노</li>
                    <li>블렌디드 음료</li>
                    <li>스타벅스 피지오</li>
                    <li>티(티바나)</li>
                    <li>기타 제조 음료</li>
                    <li>스타벅스 주스(병음료)</li>
                  </ul>
                </li>
                <li>
                  <h4>푸드</h4>
                  <ul>
                    <li>브레드</li>
                    <li>케이크</li>
                    <li>샌드위치 & 샐러드</li>
                    <li>따뜻한 푸드</li>
                    <li>과일 & 요거트</li>
                    <li>스낵 & 미니 디저트</li>
                    <li>아이스크림</li>
                  </ul>
                </li>
                <li>
                  <h4>상품</h4>
                  <ul>
                    <li>머그</li>
                    <li>글라스</li>
                    <li>플라스틱 텀블러</li>
                    <li>스테인리스 텀블러</li>
                    <li>보온병</li>
                    <li>액세서리</li>
                    <li>선물세트</li>
                    <li>커피 용품</li>
                    <li>패키지 티(티바나)</li>
                  </ul>
                </li>
                <li>
                  <h4>카드</h4>
                  <ul>
                    <li>실물카드</li>
                    <li>e-Gift 카드</li>
                  </ul>
                </li>
                <li>
                  <h4>메뉴 이야기</h4>
                  <ul>
                    <li>나이트로 콜드브루</li>
                    <li>콜드 브루</li>
                    <li>스타벅스 티바나</li>
                  </ul>
                </li>
              </ul>
            </div>
            <div class="contents__texture">
              <div class="inner">
                <h4>나이트로 콜드 브루</h4>
                <p>나이트로 커피 정통의 물결치듯 흘러내리는 캐스케이딩과 부드러운 크림을 경험하세요.</p>
              </div>
            </div>
          </div>
        </li>
        <li class="item">
          <div class="item__name">STORE</div>
          <div class="item__contents">
            <div class="contents__menu">
              <ul class="inner">
                <li>
                  <h4>매장 찾기</h4>
                  <ul>
                    <li>퀵 검색</li>
                    <li>지역 검색</li>
                  </ul>
                </li>
                <li>
                  <h4>드라이브 스루 매장</h4>
                  <ul>
                    <li></li>
                  </ul>
                </li>
                <li>
                  <h4>스타벅스 리저브TMI 매장</h4>
                  <ul>
                    <li></li>
                  </ul>
                </li>
                <li>
                  <h4>커뮤니티 스토어 매장</h4>
                  <ul>
                    <li></li>
                  </ul>
                </li>
                <li>
                  <h4>매장 이야기</h4>
                  <ul>
                    <li>티바나 바 매장</li>
                  </ul>
                </li>
              </ul>
            </div>
            <div class="contents__texture">
              <div class="inner">
                <h4>매장 찾기</h4>
                <p>보다 빠르게 매장을 찾아보세요.</p>
              </div>
            </div>
          </div>
        </li>
        <li class="item">
          <div class="item__name">RESPONSIBILITY</div>
          <div class="item__contents">
            <div class="contents__menu">
              <ul class="inner">
                <li>
                  <h4>사회공헌 캠페인 소개</h4>
                  <ul>
                    <li></li>
                  </ul>
                </li>
                <li>
                  <h4>지역 사회 참여 활동</h4>
                  <ul>
                    <li>회망배달 캠페인</li>
                    <li>재능기부 카페 소식</li>
                    <li>커뮤니티 스토어</li>
                    <li>청년인재 양성</li>
                    <li>우리 농산물 사랑 캠페인</li>
                    <li>우리 문화 지키기</li>
                  </ul>
                </li>
                <li>
                  <h4>환경보호 활동</h4>
                  <ul>
                    <li>친환경 활동</li>
                    <li>일회용 컵 없는 매장</li>
                    <li>커피 원두 재활용</li>
                  </ul>
                </li>
                <li>
                  <h4>윤리 구매</h4>
                  <ul>
                    <li>윤리적 원두 구매</li>
                    <li>공정무역 인증</li>
                    <li>커피 농가 지원 활동</li>
                  </ul>
                </li>
                <li>
                  <h4>글로벌 사회 공헌</h4>
                  <ul>
                    <li>윤리경영 보고서</li>
                    <li>스타벅스 재단</li>
                    <li>지구촌 봉사의 달</li>
                  </ul>
                </li>
              </ul>
            </div>
          </div>
        </li>
        <li class="item">
          <div class="item__name">STARBUCKS REWARDS</div>
          <div class="item__contents">
            <div class="contents__menu">
              <ul class="inner">
                <li>
                  <h4>스타벅스 리워드</h4>
                  <ul>
                    <li>스타벅스 리워드 소개</li>
                    <li>등급 및 혜택</li>
                    <li>스타벅스 별</li>
                    <li>자주하는 질문</li>
                  </ul>
                </li>
                <li>
                  <h4>스타벅스 카드</h4>
                  <ul>
                    <li>스타벅스 카드 소개</li>
                    <li>스타벅스 카드 갤러리</li>
                    <li>등록 및 조회</li>
                    <li>충전 및 이용안내</li>
                    <li>분실신고/환불신청</li>
                    <li>자주하는 질문</li>
                  </ul>
                </li>
                <li>
                  <h4>스타벅스 카드 e-Gift</h4>
                  <ul>
                    <li>스타벅스 카드 e-Gift 소개</li>
                    <li>이용안내</li>
                    <li>선물하기</li>
                    <li>자주하는 질문</li>
                  </ul>
                </li>
              </ul>
            </div>
            <div class="contents__texture">
              <div class="inner">
                <h4>스타벅스 카드 등록하기</h4>
                <p>카드 등록 후 리워드 서비스를 누리고 사용내역도 조회해보세요.</p>
              </div>
            </div>
          </div>
        </li>
        <li class="item">
          <div class="item__name">WHAT'S NEW</div>
          <div class="item__contents">
            <div class="contents__menu">
              <ul class="inner">
                <li>
                  <h4>이벤트</h4>
                  <ul>
                    <li>전체</li>
                    <li>스타벅스 카드</li>
                    <li>스타벅스 리워드</li>
                    <li>온라인</li>
                    <li>e- 프리퀀시 증정품</li>
                  </ul>
                </li>
                <li>
                  <h4>뉴스</h4>
                  <ul>
                    <li>전체</li>
                    <li>상품 출시</li>
                    <li>스타벅스와 문화</li>
                    <li>스타벅스 사회공헌</li>
                    <li>스타벅스 카드출시</li>
                  </ul>
                </li>
                <li>
                  <h4>매장별 이벤트</h4>
                  <ul>
                    <li>일반 매장</li>
                    <li>신규 매장</li>
                  </ul>
                </li>
                <li>
                  <h4>e- 프리퀀시</h4>
                  <ul>
                    <li>이용안내</li>
                    <li>이용현황</li>
                  </ul>
                </li>
                <li>
                  <h4>공지사항</h4>
                  <ul>
                    <li></li>
                  </ul>
                </li>
                <li>
                  <h4>월페이퍼</h4>
                  <ul>
                    <li></li>
                  </ul>
                </li>
              </ul>
            </div>
            <div class="contents__texture">
              <div class="inner">
                <h4>매장별 이벤트</h4>
                <p>스타벅스의 매장 이벤트 정보를 확인 하실 수 있습니다.</p>
                <h4>월페이퍼</h4>
                <p>매월 업데이트되는 월페이퍼(PC/Mobile)로 스타벅스를 더욱 가깝게 즐겨보세요!</p>
              </div>
            </div>
          </div>
        </li>
      </ul>
```
