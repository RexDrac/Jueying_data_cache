batch-size: 128
total-step-num: 2500000000
critic-l2-reg: 0.0003
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
max-step-num: 2500000000
max-test-time: 10
expert-num: 4
reward-scale: 0.1
replay-ratio: 1
env-id: HumanoidBalanceFilter-v0
gating-index: None
Physics-frequency: 1000
action-dim: 12
critic-layer-size: [256, 256]
render-eval: False
interpolation: False
expert-index: None
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
loss-output-bound-coeff: 0.0
tau: 0.001
actor-activation-fn: ['relu', 'relu', 'None']
epoch-step-num: 5000000
critic-lr: 0.0003
gating-activation-fn: ['relu', 'relu', 'None']
gating-layer-size: [32, 32]
state-dim: 18
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
max-path-step: 5000
epoch-num: 500
squash-action: True
gamma: 0.995
filter-action: True
task-weight: 0.0
HLC-frequency: 25
n-step: 1
filter-torque: False
prioritized-exp-replay: True
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
LLC-frequency: 500
actor-layer-size: [256, 256]
max-path-num: 20
bullet-default-PD: False
max-train-time: 10
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
actor-weight-decay: 1e-06
max-episode-num: 5000000
loss-output-diff-coeff: 0
replay-start-size: 10000
record-start-size: 10000.0
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
imitation-weight: 1.0
critic-weight-decay: 1e-06
actor-lr: 0.0003
test-num: 4
categorical-distribution: {'n_atoms': 51, 'v_min': -10, 'v_max': 250}
loss-entropy-coeff: 0.0
actor-l2-reg: 0.0003
loss-output-smooth-coeff: 1.0
replay-buffer-size: 1000000
critic-activation-fn: ['relu', 'relu', 'None']
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
train-step-num: 1
joint-interpolation: True
rollout-step-num: 1
