reward-scale: 0.1
gating-index: None
env-id: HumanoidBalanceFilter-v0
actor-activation-fn: ['relu', 'relu', 'None']
action-dim: 12
interpolation: False
expert-index: None
replay-ratio: 1
test-num: 4
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
epoch-num: 500
tau: 0.001
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
actor-layer-size: [256, 256]
gating-layer-size: [32, 32]
max-path-num: 20
HLC-frequency: 25
filter-torque: False
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
gamma: 0.995
critic-lr: 0.0003
critic-layer-size: [256, 256]
critic-weight-decay: 1e-06
max-step-num: 2500000000
critic-l2-reg: 0.0003
max-test-time: 10
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
actor-l2-reg: 0.0003
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
Physics-frequency: 1000
epoch-step-num: 5000000
replay-buffer-size: 1000000
squash-action: True
loss-entropy-coeff: 0.0
categorical-distribution: {'n_atoms': 51, 'v_max': 250, 'v_min': -10}
task-weight: 0.0
loss-output-diff-coeff: 0
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
actor-lr: 0.0003
total-step-num: 2500000000
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
loss-output-bound-coeff: 0.0
loss-output-smooth-coeff: 2.0
LLC-frequency: 500
render-eval: False
rollout-step-num: 1
max-train-time: 10
max-episode-num: 5000000
joint-interpolation: True
critic-activation-fn: ['relu', 'relu', 'None']
filter-action: True
bullet-default-PD: False
n-step: 1
batch-size: 128
train-step-num: 1
replay-start-size: 10000
record-start-size: 10000.0
expert-num: 4
prioritized-exp-replay: True
imitation-weight: 1.0
max-path-step: 5000
actor-weight-decay: 1e-06
state-dim: 18
gating-activation-fn: ['relu', 'relu', 'None']
