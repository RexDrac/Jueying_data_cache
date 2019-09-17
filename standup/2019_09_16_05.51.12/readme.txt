gating-layer-size: [32, 32]
max-episode-num: 5000000
gating-index: None
batch-size: 128
replay-ratio: 1
rollout-step-num: 1
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
critic-l2-reg: 0.0003
expert-index: None
epoch-num: 500
max-step-num: 2500000000
max-train-time: 10
actor-activation-fn: ['relu', 'relu', 'None']
LLC-frequency: 500
Physics-frequency: 1000
imitation-weight: 1.0
interpolation: False
action-dim: 12
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
record-start-size: 10000.0
joint-interpolation: True
actor-l2-reg: 0.0003
replay-start-size: 10000
critic-layer-size: [256, 256]
n-step: 1
expert-num: 4
actor-layer-size: [256, 256]
epoch-step-num: 5000000
critic-weight-decay: 1e-06
max-path-step: 5000
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
replay-buffer-size: 1000000
loss-output-diff-coeff: 0
max-test-time: 10
state-dim: 18
reward-scale: 0.1
squash-action: True
filter-torque: False
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
prioritized-exp-replay: True
max-path-num: 20
gamma: 0.995
HLC-frequency: 25
env-id: HumanoidBalanceFilter-v0
train-step-num: 1
filter-action: True
task-weight: 0.0
tau: 0.001
loss-entropy-coeff: 0.0
critic-activation-fn: ['relu', 'relu', 'None']
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
test-num: 4
render-eval: False
critic-lr: 0.0003
categorical-distribution: {'n_atoms': 51, 'v_min': -10, 'v_max': 250}
bullet-default-PD: False
gating-activation-fn: ['relu', 'relu', 'None']
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
actor-weight-decay: 1e-06
actor-lr: 0.0003
loss-output-bound-coeff: 0.0
loss-output-smooth-coeff: 2.0
total-step-num: 2500000000
