실용주의 머신러닝 3주차 숙제입니다.

1. build from sources: https://www.tensorflow.org/install/install_source

2. 유닛테스트 작성 및 테스트: 그냥 tensorflow home에 있는 unit test 사용하였습니다.

{{{
hyunkiui-MacBook-Pro:tensorflow_unit_test hkbaik$ python tensorflow_squretest.py 
2017-07-16 10:48:44.831216: W tensorflow/core/platform/cpu_feature_guard.cc:45] The TensorFlow library wasn't compiled to use SSE4.2 instructions, but these are available on your machine and could speed up CPU computations.
2017-07-16 10:48:44.831237: W tensorflow/core/platform/cpu_feature_guard.cc:45] The TensorFlow library wasn't compiled to use AVX instructions, but these are available on your machine and could speed up CPU computations.
2017-07-16 10:48:44.831243: W tensorflow/core/platform/cpu_feature_guard.cc:45] The TensorFlow library wasn't compiled to use AVX2 instructions, but these are available on your machine and could speed up CPU computations.
2017-07-16 10:48:44.831247: W tensorflow/core/platform/cpu_feature_guard.cc:45] The TensorFlow library wasn't compiled to use FMA instructions, but these are available on your machine and could speed up CPU computations.
..
----------------------------------------------------------------------
Ran 2 tests in 0.022s
}}}
