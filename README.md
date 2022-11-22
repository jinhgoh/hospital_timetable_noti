# hospital_timetable_noti
Hospital timetable notification sytem using Google Apps Scripts & Slack Webhook

* 영상의학과 진료순서표는 google spreadsheet로 작성되어 각 과(내과/외과 등)에서 스스로 접수를 한다. 갑작스럽게 환자가 밀고 들어 올때가 있어서 일일히 체크하기가 번거로웠음.
* Google script apps 와 Slack 의 webhook 기능을 이용해, 내 환자가 내원하거나 or 내가 주치의로 배정되거나 or 우리 진료조의 CT, MR 촬영이 잡힐 시 자동으로 알림이 오게하는 코드를 작성함.
* 진료표를 열어보는 횟수가 10~20회/day 에서 0회/day 로 감소함.
