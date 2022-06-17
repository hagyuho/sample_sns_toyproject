**풀스택 리액트 토이프로젝트**

- 인프런에서 풀스택 리액트 토이프로젝트 강의 (by 재남)를 들으며 작성한 코드입니다.
- 간단한 SNS 기능을 개발하며 FE(react, reactQuary, nextJs), BE(nodeExpress, graphQl) 개발 클론코딩을 진행했습니다.

**디렉토리 구조**

client (FE)
├── .next/              : next 기본 설정파일 디렉토리
├── components/         : react 컴포넌트
├── graphql/            : graphql로 호출할 query/mutation 명세 정의
├── hooks/              : 내부적으로 사용할 hook 정의 ( 인피니티 스크롤 훅 )
├── node_modules/
├── pages/
|   ├── _apps.js        : react / next.js 통해 호출되는 App 정의
|   └──  index.js       : 
├── fetcher.js          : 서버 연동 위한 axios 커스터마이징 (Rest)
├── next.config.js      : next사용 시 기본 경로 지정 
├── package.js          : 프로젝트 config 파일 
└── queryClient.js      : 서버 연동 위한 graphQl Request 커스터마이징 ( graphql ) / reactQuery key 정보 / data processing 처리


server  (BE)
├── node_modules/
├── src/
|   ├── db/             : json으로 mock DB 설정
|   ├── resolver/       : graphql 기반 API 작성 (query / mutation )
|   ├── routes/         : rest 기반 API 작성 ( get / post / put / delete )
|   ├── schema/         : graphql 기반 스키마 정보 작성
|   ├── dbController.js : mock DB 연동 controller ( read/write) 
|   └── index.js        : node-express 서버 구동 
├── nodemon.json        : 서버 연동 위한 axios 커스터마이징 (Rest)
└── package.json        : 서버 연동 위한 graphQl Request 커스터마이징 ( graphql ) / reactQuery key 정보 / data processing 처리




- react        : 

- reactQuary   : QueryClientProvider / Hydrate / QueryClient / useQuery / useInfinityQuery / mutation / 
- 
- nextJs       : getServerSideProps 통해 ssr 처리

- nodeExpress  : 

- graphQl      :
