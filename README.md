# courm-platform

클러스터 공통(Platform) 리소스 저장소입니다.

현재 범위(요청 기준):
- Istio 설치 시 사용하는 Helm values (`istio/values/*`)
- Kubernetes Gateway API 리소스 (`gateway-api/*`)  
  - `GatewayClass` + `Gateway(dev/prod)`

> 실제 배포는 `courm-bootstrap` 레포의 Argo CD Application들이 이 레포를 가리켜서 이루어집니다.
