test-num: 4
gating-layer-size: [32, 32]
max-test-time: 10
filter-torque: False
action-dim: 12
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
gating-index: None
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
epoch-step-num: 5000000
expert-num: 4
expert-index: None
actor-l2-reg: 0.0003
env-id: HumanoidBalanceFilter-v0
loss-output-diff-coeff: 0
critic-lr: 0.0003
max-path-num: 20
epoch-num: 500
reward-scale: 0.1
gamma: 0.995
loss-output-bound-coeff: 0.0
record-start-size: 10000.0
actor-lr: 0.0003
max-episode-num: 5000000
max-train-time: 10
render-eval: False
filter-action: True
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
tau: 0.001
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
critic-weight-decay: 1e-06
Physics-frequency: 1000
bullet-default-PD: False
critic-layer-size: [256, 256]
loss-output-smooth-coeff: 1.0
train-step-num: 1
gating-activation-fn: ['relu', 'relu', 'None']
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
max-path-step: 5000
replay-start-size: 10000
max-step-num: 2500000000
loss-entropy-coeff: 0.0
joint-interpolation: True
imitation-weight: 1.0
interpolation: False
critic-l2-reg: 0.0003
replay-ratio: 1
batch-size: 128
actor-activation-fn: ['relu', 'relu', 'None']
total-step-num: 2500000000
state-dim: 18
squash-action: True
HLC-frequency: 25
categorical-distribution: {'n_atoms': 51, 'v_max': 250, 'v_min': -10}
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
n-step: 1
task-weight: 0.0
prioritized-exp-replay: True
critic-activation-fn: ['relu', 'relu', 'None']
actor-layer-size: [256, 256]
replay-buffer-size: 1000000
rollout-step-num: 1
actor-weight-decay: 1e-06
LLC-frequency: 500
