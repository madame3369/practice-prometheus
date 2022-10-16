# practice-prometheus
모니터링 환경 구축 복습
요구사항 
- 기존 Default 값으로 설치 시 1시간마다 저장되는 데이터가 삭제됨 -> 1년 or 10년 등 설정하는 옵션추가 하는 법 
https://github.com/prometheus-operator/prometheus-operator/blob/22aaf848a27f6e45702131e22a596778686068d5/Documentation/api.md#prometheusspec
https://github.com/prometheus-operator/kube-prometheus/issues/840

- PV, PVC, Storageclass로 로컬노드에 저장하는 방식으로 프로메테우스를 내렸다가 올려도 기존 수집 데이터가 유지되도록 하기

