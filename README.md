# Zero-Cost Proxy for Adversarial Robustsness Evaluation
Official Codes for the paper "Zero-Cost Proxy for Adversarial Robustsness Evaluation"

Requirements:

Python == 3.7, PyTorch == 1.6.0, torchvision == 0.7.0

To search for adversarially robust architectures:

cd ./exps/NAS-RF
python search_robust.py

To test Kendall¡¯s Tau correlation coefficients of the previous zero-cost proxies:

cd ./exps/NAS-RF
python test_zero_cost_previous.py

To test Kendall¡¯s Tau correlation coefficient of the proposed zero-cost proxy:

cd ./exps/NAS-RF
python test_zero_cost_robust.py


The constructed dataset in this paper, i.e., Tiny-RobustBench, is also provided in the following directory:

./exps/NAS-RF/robust_arch_dataset

We made innovations based on the codes of KNAS.

@inproceedings{knas,
  title = {KNAS: Green Neural Architecture Search},
  author= {Jingjing Xu and
               Liang Zhao and
               Junyang Lin and
               Rundong Gao and
               Xu Sun and
               Hongxia Yang},
  booktitle = {Proceedings of ICML 2021},
  year = {2021},
}




