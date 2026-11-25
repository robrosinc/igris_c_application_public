# Changelog

Changes in each IGRIS-C Application release. Every release lists the changes
in English first, then in Korean.

<!--
How to add a release (internal note, also published):
  - Add a `## vX.Y.Z` section at the top, matching the release tag exactly.
  - Write for people operating the robot: what changed for them, not how.
  - No ticket keys, internal paths or service names.
  - Jenkins publishes this section as the GitHub Release notes and fails
    the release build if the section is missing.
-->

## v2.1.1

### English
- The app's license terms (`LICENSE`) and the notices of the third-party components it bundles
  (`NOTICE`) are now published with the release.
- The license text of the bundled Pretendard font (SIL Open Font License 1.1) is included in the
  app package.
- The app's behaviour is unchanged since v2.1.0.

### 한국어
- 앱의 라이선스 조건(`LICENSE`)과 함께 들어 있는 서드파티 구성 요소의 고지(`NOTICE`)를 릴리스와 함께
  공개합니다.
- 앱에 들어 있는 Pretendard 폰트의 라이선스 전문(SIL Open Font License 1.1)을 앱 패키지에 넣었습니다.
- 앱 동작은 v2.1.0과 같습니다.

## v2.1.0

### English
- First release published on GitHub. The app is unchanged since v2.0.6.

### 한국어
- GitHub에 처음 배포하는 릴리스입니다. 앱은 v2.0.6 이후 변경 사항이 없습니다.

## v2.0.6

### English
- Refreshed the UI across the splash screen, connection, control, monitoring
  and dialog screens.
- The monitoring panel can show joint angles and IMU roll/pitch/yaw in either
  degrees or radians, switched from the panel header.
- Fixed the IMU value conversion between radians and degrees.
- The Motion Stop lock now follows the robot's return-to-home state, so
  the lock shown in the app matches the robot.
- Upgraded the Android build toolchain.

### 한국어
- 스플래시, 연결, 제어, 모니터링, 대화상자 화면의 UI를 개편했습니다.
- 모니터링 패널에서 관절 각도와 IMU roll/pitch/yaw를 도(degree)와
  라디안(radian) 중 선택해 볼 수 있습니다. 패널 헤더에서 전환합니다.
- IMU 값의 라디안·도 변환 오류를 수정했습니다.
- Motion Stop 잠금 상태를 로봇의 복귀(return-to-home) 상태에 맞춰 판단하므로,
  앱에 표시되는 잠금 상태가 로봇과 일치합니다.
- Android 빌드 툴체인을 업그레이드했습니다.
