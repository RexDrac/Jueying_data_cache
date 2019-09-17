train-step-num: 1
rollout-step-num: 1
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
loss-entropy-coeff: 0.0
gating-layer-size: [32, 32]
n-step: 1
filter-action: True
replay-ratio: 1
filter-torque: False
reward-scale: 0.1
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
batch-size: 128
tau: 0.001
epoch-step-num: 5000000
state-dim: 18
epoch-num: 500
LLC-frequency: 500
max-episode-num: 5000000
actor-l2-reg: 0.0003
max-step-num: 2500000000
categorical-distribution: {'n_atoms': 51, 'v_min': -10, 'v_max': 250}
interpolation: False
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
critic-activation-fn: ['relu', 'relu', 'None']
max-train-time: 10
replay-buffer-size: 1000000
env-id: HumanoidBalanceFilter-v0
render-eval: False
HLC-frequency: 25
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
gating-activation-fn: ['relu', 'relu', 'None']
actor-weight-decay: 1e-06
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
task-weight: 0.0
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
expert-num: 4
max-path-num: 20
loss-output-diff-coeff: 0
bullet-default-PD: False
critic-lr: 0.0003
Physics-frequency: 1000
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
critic-weight-decay: 1e-06
action-dim: 12
test-num: 4
squash-action: True
actor-activation-fn: ['relu', 'relu', 'None']
max-path-step: 5000
record-start-size: 10000.0
loss-output-smooth-coeff: 2.0
replay-start-size: 10000
expert-index: None
prioritized-exp-replay: True
total-step-num: 2500000000
critic-l2-reg: 0.0003
joint-interpolation: True
gamma: 0.995
gating-index: None
actor-layer-size: [256, 256]
loss-output-bound-coeff: 0.0
imitation-weight: 1.0
critic-layer-size: [256, 256]
max-test-time: 10
actor-lr: 0.0003
