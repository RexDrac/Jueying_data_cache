reward-scale: 0.1
HLC-frequency: 25
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
epoch-num: 500
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
critic-lr: 0.0003
state-dim: 23
LLC-frequency: 500
filter-torque: False
train-step-num: 1
loss-entropy-coeff: 0.0
expert-num: 4
replay-buffer-size: 1000000
loss-output-bound-coeff: 0.0
actor-layer-size: [256, 256]
actor-weight-decay: 1e-06
max-path-step: 5000
batch-size: 128
prioritized-exp-replay: True
rollout-step-num: 1
gating-index: None
n-step: 1
bullet-default-PD: False
actor-activation-fn: ['relu', 'relu', 'None']
squash-action: True
replay-ratio: 1
max-step-num: 2500000000
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
task-weight: 0.5
render-eval: False
critic-layer-size: [256, 256]
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
dsr-gait-period: 0.6
categorical-distribution: {'n_atoms': 51, 'v_min': -10, 'v_max': 250}
gamma: 0.955
loss-output-smooth-coeff: 1.0
max-test-time: 10
expert-index: None
dsr-gait-freq: 1.667
actor-lr: 0.0003
total-step-num: 2500000000
interpolation: False
replay-start-size: 10000
critic-l2-reg: 0.0003
filter-action: True
action-dim: 12
env-id: HumanoidBalanceFilter-v0
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
max-episode-num: 5000000
test-num: 4
imitation-weight: 0.5
gating-activation-fn: ['relu', 'relu', 'None']
joint-interpolation: True
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
max-train-time: 10
critic-activation-fn: ['relu', 'relu', 'None']
actor-l2-reg: 0.0003
record-start-size: 10000.0
loss-output-diff-coeff: 0
max-path-num: 20
gating-layer-size: [32, 32]
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
critic-weight-decay: 1e-06
tau: 0.001
Physics-frequency: 1000
epoch-step-num: 5000000
