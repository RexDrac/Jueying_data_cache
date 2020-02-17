replay-start-size: 10000
critic-weight-decay: 1e-06
max-test-time: 10
actor-layer-size: [256, 256]
n-step: 1
prioritized-exp-replay: True
max-episode-num: 5000000
test-num: 4
gating-layer-size: [32, 32]
batch-size: 128
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
loss-output-smooth-coeff: 2.0
env-id: HumanoidBalanceFilter-v0
render-eval: False
max-train-time: 10
replay-ratio: 1
replay-buffer-size: 1000000
actor-l2-reg: 0.0003
gating-activation-fn: ['relu', 'relu', 'None']
actor-activation-fn: ['relu', 'relu', 'None']
gamma: 0.995
train-step-num: 1
expert-index: None
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
action-dim: 12
tau: 0.001
critic-activation-fn: ['relu', 'relu', 'None']
loss-output-diff-coeff: 0
filter-torque: False
HLC-frequency: 25
actor-weight-decay: 1e-06
max-step-num: 2500000000
loss-output-bound-coeff: 0.0
gating-index: None
categorical-distribution: {'n_atoms': 51, 'v_min': -10, 'v_max': 250}
LLC-frequency: 500
filter-action: True
squash-action: True
state-dim: 18
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
max-path-step: 5000
Physics-frequency: 1000
epoch-num: 500
critic-layer-size: [256, 256]
interpolation: False
imitation-weight: 1.0
critic-l2-reg: 0.0003
expert-num: 4
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
reward-scale: 0.1
epoch-step-num: 5000000
record-start-size: 10000.0
task-weight: 0.0
max-path-num: 20
total-step-num: 2500000000
loss-entropy-coeff: 0.0
bullet-default-PD: False
critic-lr: 0.0003
joint-interpolation: True
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
rollout-step-num: 1
actor-lr: 0.0003
