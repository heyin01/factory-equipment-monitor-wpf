# Factory Equipment Monitor (WPF)

## 1. 프로젝트 목적
- 공정 설비의 상태 데이터를 시각화하는 WPF 기반 모니터링 UI 구현
- MVVM 구조를 적용하여 유지보수성과 확장성을 고려한 설계 연습

## 2. 기술 스택
- WPF (.NET 6)
- C#
- MVVM Pattern
- ICommand (RelayCommand)
- ObservableCollection
- DataBinding

## 3. 구조 개요
- Model: 설비 상태 데이터 클래스 (Status, Temperature, Alarm)
- ViewModel: ObservableCollection로 설비 목록 관리 및 Command 처리
- View: DataGrid 기반 UI + 상태 색상 바인딩

## 4. 향후 확장 계획
- Modbus/TCP 기반 PLC 통신 모듈 추가
- 실시간 차트 기능 구현
- 알람 로그 저장 및 CSV Export 기능 추가
