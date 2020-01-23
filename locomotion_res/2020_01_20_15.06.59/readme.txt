action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
replay-start-size: 10000
state-dim: 23
env-id: HumanoidBalanceFilter-v0
critic-activation-fn: ['relu', 'relu', 'None']
HLC-frequency: 25
total-step-num: 2500000000
max-train-time: 10
prioritized-exp-replay: True
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
loss-output-smooth-coeff: 2.0
reward-scale: 0.1
loss-output-bound-coeff: 0.0
Physics-frequency: 1000
actor-lr: 0.0003
record-start-size: 10000.0
max-path-num: 20
dsr-gait-freq: 1.667
batch-size: 128
render-eval: False
rollout-step-num: 1
filter-torque: False
expert-index: None
replay-ratio: 1
actor-layer-size: [256, 256]
critic-weight-decay: 1e-06
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
gating-activation-fn: ['relu', 'relu', 'None']
squash-action: True
epoch-step-num: 5000000
LLC-frequency: 500
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
max-path-step: 5000
categorical-distribution: {'n_atoms': 51, 'v_min': -10, 'v_max': 250}
n-step: 1
max-test-time: 10
gamma: 0.955
gating-index: None
dsr-gait-period: 0.6
loss-output-diff-coeff: 0
task-weight: 0.5
max-step-num: 2500000000
joint-interpolation: True
filter-action: True
actor-activation-fn: ['relu', 'relu', 'None']
bullet-default-PD: False
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
test-num: 4
critic-lr: 0.0003
max-episode-num: 5000000
critic-layer-size: [256, 256]
imitation-weight: 0.5
actor-l2-reg: 0.0003
gating-layer-size: [32, 32]
action-dim: 12
loss-entropy-coeff: 0.0
replay-buffer-size: 1000000
actor-weight-decay: 1e-06
train-step-num: 1
expert-num: 4
interpolation: False
tau: 0.001
critic-l2-reg: 0.0003
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
epoch-num: 500
