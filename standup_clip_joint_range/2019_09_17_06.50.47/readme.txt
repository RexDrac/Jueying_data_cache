action-dim: 12
filter-torque: False
replay-buffer-size: 1000000
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
critic-layer-size: [256, 256]
gating-index: None
batch-size: 128
state-dim: 18
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
replay-start-size: 10000
critic-l2-reg: 0.0003
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
actor-activation-fn: ['relu', 'relu', 'None']
replay-ratio: 1
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
critic-activation-fn: ['relu', 'relu', 'None']
task-weight: 0.0
squash-action: True
joint-interpolation: True
actor-l2-reg: 0.0003
interpolation: False
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
reward-scale: 0.1
loss-entropy-coeff: 0.0
max-step-num: 2500000000
expert-num: 4
env-id: HumanoidBalanceFilter-v0
imitation-weight: 1.0
actor-lr: 0.0003
prioritized-exp-replay: True
total-step-num: 2500000000
actor-layer-size: [256, 256]
HLC-frequency: 25
LLC-frequency: 500
bullet-default-PD: False
epoch-step-num: 5000000
max-episode-num: 5000000
train-step-num: 1
gating-layer-size: [32, 32]
critic-lr: 0.0003
max-path-step: 5000
tau: 0.001
actor-weight-decay: 1e-06
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
filter-action: True
max-test-time: 10
rollout-step-num: 1
max-path-num: 20
loss-output-smooth-coeff: 2.0
render-eval: False
gating-activation-fn: ['relu', 'relu', 'None']
expert-index: None
test-num: 4
max-train-time: 10
loss-output-bound-coeff: 0.0
Physics-frequency: 1000
epoch-num: 500
critic-weight-decay: 1e-06
gamma: 0.995
categorical-distribution: {'n_atoms': 51, 'v_min': -10, 'v_max': 250}
record-start-size: 10000.0
n-step: 1
loss-output-diff-coeff: 0
