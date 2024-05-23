cert manager letsencrypt

준비
외부 통신이 되는 환경
도메인과 cloudflare 연동
쿠버네티스 클러스터
cert-manager 설치
cloudflare api token을 생성하고 쿠버네티스 secret에 저장
cloudflare api-token -> k8s secret 생성방법: https://cert-manager.io/docs/configuration/acme/dns01/cloudflare/#api-keys

