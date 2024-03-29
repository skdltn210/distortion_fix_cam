# distortion_fix_cam
Correcting Lens Distortion Through Camera Calibration with OpenCV

## Contents

* camera_calibration.py - 체커보드 영상을 받고 체커보드의 개수와 사이즈를 입력해 카메라 캘리브레이션을 수행합니다.
* distortion_correction.py - camera_calibration.py에서 얻은 매개변수들을 넣어 영상의 렌즈 왜곡을 보정합니다.
* checkerboard.avi - 체커보드 예제 영상입니다.
* calibration_result.npz - 캘리브레이션의 결과 파일입니다.

## 캘리브레이션 결과

* 카메라 내부 매개 변수 (행렬 형태):
[[887.85145863   0.         958.72123757]
 [  0.         886.52280175 539.18402062]
 [  0.           0.           1.        ]]

* 카메라 내부 매개 변수:
(fx, fy, cx, cy, ..., rmse): (887.8514586280374, 886.5228017457406, 958.7212375744868, 539.1840206163621, ..., 0.8716776088117677)

* 렌즈 왜곡 매개 변수:
[[-1.40187002e-02  4.48743164e-03  1.34338042e-03 -3.10858207e-04
  -5.01705656e-05]]

## 렌즈 왜곡 보정 결과

https://github.com/skdltn210/distortion_fix_cam/assets/113167709/8c9d0c55-536c-4661-bdbe-2882198ad44b


