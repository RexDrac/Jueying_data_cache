rollout-step-num: 1
HLC-frequency: 25
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
squash-action: True
actor-lr: 0.0003
prioritized-exp-replay: True
categorical-distribution: {'n_atoms': 51, 'v_min': -10, 'v_max': 250}
replay-ratio: 1
replay-buffer-size: 1000000
gamma: 0.955
imitation-weight: 0.5
loss-output-bound-coeff: 0.0
critic-lr: 0.0003
record-start-size: 10000.0
expert-index: None
critic-activation-fn: ['relu', 'relu', 'None']
epoch-step-num: 5000000
task-weight: 0.5
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
batch-size: 128
state-dim: 23
max-step-num: 2500000000
action-dim: 12
dsr-gait-period: 0.6
actor-activation-fn: ['relu', 'relu', 'None']
loss-output-smooth-coeff: 2.0
expert-num: 4
max-train-time: 10
LLC-frequency: 500
total-step-num: 2500000000
critic-layer-size: [256, 256]
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
test-num: 4
render-eval: False
joint-interpolation: True
filter-action: True
tau: 0.001
gating-activation-fn: ['relu', 'relu', 'None']
filter-torque: False
Physics-frequency: 1000
env-id: HumanoidBalanceFilter-v0
max-episode-num: 5000000
interpolation: False
actor-layer-size: [256, 256]
actor-l2-reg: 0.0003
max-path-num: 20
actor-weight-decay: 1e-06
reward-scale: 0.1
bullet-default-PD: False
train-step-num: 1
gating-index: None
loss-entropy-coeff: 0.0
replay-start-size: 10000
gating-layer-size: [32, 32]
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
loss-output-diff-coeff: 0
critic-weight-decay: 1e-06
max-path-step: 5000
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
n-step: 1
critic-l2-reg: 0.0003
max-test-time: 10
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
epoch-num: 500
dsr-gait-freq: 1.667
