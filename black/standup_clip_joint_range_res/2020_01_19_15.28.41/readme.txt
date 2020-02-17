categorical-distribution: {'n_atoms': 51, 'v_min': -10, 'v_max': 250}
actor-l2-reg: 0.0003
max-path-num: 20
reward-scale: 0.1
gamma: 0.995
replay-ratio: 1
max-path-step: 5000
actor-layer-size: [256, 256]
loss-entropy-coeff: 0.0
total-step-num: 2500000000
state-dim: 18
record-start-size: 10000.0
gating-activation-fn: ['relu', 'relu', 'None']
joint-interpolation: True
interpolation: False
max-test-time: 10
task-weight: 0.0
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
critic-layer-size: [256, 256]
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
env-id: HumanoidBalanceFilter-v0
critic-lr: 0.0003
bullet-default-PD: False
n-step: 1
train-step-num: 1
epoch-num: 500
imitation-weight: 1.0
critic-activation-fn: ['relu', 'relu', 'None']
actor-weight-decay: 1e-06
gating-index: None
max-train-time: 10
prioritized-exp-replay: True
max-step-num: 2500000000
tau: 0.001
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
LLC-frequency: 500
critic-weight-decay: 1e-06
replay-start-size: 10000
critic-l2-reg: 0.0003
expert-index: None
render-eval: False
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
epoch-step-num: 5000000
rollout-step-num: 1
squash-action: True
HLC-frequency: 25
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
filter-action: True
actor-activation-fn: ['relu', 'relu', 'None']
filter-torque: False
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
action-dim: 12
max-episode-num: 5000000
actor-lr: 0.0003
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
gating-layer-size: [32, 32]
batch-size: 128
replay-buffer-size: 1000000
loss-output-smooth-coeff: 2.0
loss-output-bound-coeff: 0.0
expert-num: 4
test-num: 4
Physics-frequency: 1000
loss-output-diff-coeff: 0
