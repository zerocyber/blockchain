# 이벤트 추첨 컨트랙트

특정 ERC721 NFT 홀더를 대상으로 이벤트 경품을 무작위로 추첨하여 기록하는 컨트랙트입니다.

사용 방법
1. addEvent 메소드를 통해 이벤트 정보를 등록합니다.
2. addGift 메소드를 통해 경품 정보를 등록합니다.
3. drawRandomWinnerFromHolder 메소드를 통해 무작위 당첨자를 추첨합니다.
4. getWinnerList 메소드 혹은 WinnerDrawed Event 기록을 통해 추첨 결과를 확인합니다.