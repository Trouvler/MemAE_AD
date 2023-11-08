# MemAE_AD

#### 개발자
- 인공지능 모델링 성승제 : git(https://github.com/Trouvler)
- EDA 송지혜 : git()
## 개발 배경
*  본 프로젝트는 공정의 문제 현황 파악 및 조치의 어려움, 제조 공정의 손실 증가 등의 이슈를 극복하기 위해 데이터와 기계학습을 활용한 예지보전 AI모델로 효율적인 설비관리를 도모하고자 함

* 프로젝트에서 제안하는 AI 모델의 구조는 Memory Auto Encoder와 적대적 학습을 활용하여 AE의 재구성에서 정상데이터와 유사한 이상치를 구분하지 못하는 한계를 적대적 학습으로 극복하였으며, GAN 기반 이상 탐지 모델이 학습의 불안정한 부분을 AE 기반의 모델과 결합하여 해결하여 안정적인 학습과 F1-Score 0.95를 달성하였으며 모델의 배포를 위하여 Inference 시간을 측정한 결과 데이터당 0.0018밀리 초로 빠른 속도를 나타내어 임베디드 시스템에 적용 가능성이 큼

* 본 프로젝트의 모델은 단순한 구조와 비지도 학습으로 빠른 속도와 정확도를 가져 중소 제조 기업의 다양한 공정에 적용할 수 있으며 이를 통해 중소 제조 기업은 공정 관리의 효율성을 증대시키고, 사고 예방, 수익성 증가 등으로 이어질 것으로 기대됨  


# APP
# 개발환경
- 개발언어 : python
- 프레임워크 : pytorch

# Reference
- 1. Kingma, Diederik P., and Max Welling. "Auto-encoding variational bayes." arXiv preprint arXiv:1312.6114 (2013).
- 2. Gong, Dong, et al. "Memorizing normality to detect anomaly: Memory-augmented deep autoencoder for unsupervised anomaly detection." Proceedings of the IEEE/CVF International Conference on Computer Vision. 2019.
- 3. Audibert, Julien, et al. "Usad: Unsupervised anomaly detection on multivariate time series." Proceedings of the 26th ACM SIGKDD international conference on knowledge discovery & data mining. 2020.
