env-id: HumanoidBalanceFilter-v0
gating-activation-fn: ['relu', 'relu', 'None']
max-train-time: 10
expert-num: 4
gating-index: None
loss-output-bound-coeff: 0.0
categorical-distribution: {'n_atoms': 51, 'v_min': -10, 'v_max': 250}
bullet-default-PD: False
critic-layer-size: [256, 256]
actor-layer-size: [256, 256]
prioritized-exp-replay: True
replay-start-size: 10000
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
max-step-num: 2500000000
loss-entropy-coeff: 0.0
record-start-size: 10000.0
Physics-frequency: 1000
filter-action: True
task-weight: 0.0
action-dim: 12
gating-layer-size: [32, 32]
expert-index: None
HLC-frequency: 25
n-step: 1
actor-weight-decay: 1e-06
batch-size: 128
actor-activation-fn: ['relu', 'relu', 'None']
render-eval: False
total-step-num: 2500000000
filter-torque: False
rollout-step-num: 1
actor-lr: 0.0003
actor-l2-reg: 0.0003
max-episode-num: 5000000
critic-weight-decay: 1e-06
critic-activation-fn: ['relu', 'relu', 'None']
replay-buffer-size: 1000000
max-path-step: 5000
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
critic-lr: 0.0003
squash-action: True
max-path-num: 20
max-test-time: 10
joint-interpolation: True
replay-ratio: 1
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
train-step-num: 1
epoch-step-num: 5000000
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
interpolation: False
loss-output-smooth-coeff: 2.0
state-dim: 18
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
LLC-frequency: 500
epoch-num: 500
imitation-weight: 1.0
tau: 0.001
reward-scale: 0.1
test-num: 4
loss-output-diff-coeff: 0
gamma: 0.995
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
critic-l2-reg: 0.0003
