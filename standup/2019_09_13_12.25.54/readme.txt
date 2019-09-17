n-step: 1
interpolation: False
task-weight: 0.0
max-episode-num: 5000000
epoch-num: 500
gating-activation-fn: ['relu', 'relu', 'None']
record-start-size: 10000.0
total-step-num: 2500000000
state-dim: 18
bullet-default-PD: False
actor-activation-fn: ['relu', 'relu', 'None']
test-num: 4
epoch-step-num: 5000000
loss-entropy-coeff: 0.0
max-path-num: 20
critic-layer-size: [256, 256]
prioritized-exp-replay: True
critic-activation-fn: ['relu', 'relu', 'None']
env-id: HumanoidBalanceFilter-v0
batch-size: 128
joint-interpolation: True
critic-lr: 0.0003
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
max-step-num: 2500000000
gamma: 0.995
replay-start-size: 10000
filter-torque: False
actor-l2-reg: 0.0003
actor-weight-decay: 1e-06
replay-buffer-size: 1000000
Physics-frequency: 1000
train-step-num: 1
HLC-frequency: 25
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
render-eval: False
tau: 0.001
replay-ratio: 1
max-path-step: 5000
max-train-time: 10
loss-output-diff-coeff: 0
expert-num: 4
LLC-frequency: 500
gating-index: None
loss-output-smooth-coeff: 1.0
reward-scale: 0.1
filter-action: True
imitation-weight: 1.0
actor-layer-size: [256, 256]
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
max-test-time: 10
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
squash-action: True
action-dim: 12
critic-l2-reg: 0.0003
rollout-step-num: 1
gating-layer-size: [32, 32]
categorical-distribution: {'n_atoms': 51, 'v_min': -10, 'v_max': 250}
expert-index: None
loss-output-bound-coeff: 0.0
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
actor-lr: 0.0003
critic-weight-decay: 1e-06
