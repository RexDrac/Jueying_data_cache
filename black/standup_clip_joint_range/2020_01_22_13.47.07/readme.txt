filter-action: True
filter-torque: False
replay-ratio: 1
gamma: 0.995
loss-output-diff-coeff: 0
squash-action: True
tau: 0.001
prioritized-exp-replay: True
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
record-start-size: 10000.0
LLC-frequency: 500
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
gating-layer-size: [32, 32]
gating-activation-fn: ['relu', 'relu', 'None']
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
test-num: 4
actor-l2-reg: 0.0003
replay-start-size: 10000
actor-activation-fn: ['relu', 'relu', 'None']
critic-lr: 0.0003
bullet-default-PD: False
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
Physics-frequency: 1000
joint-interpolation: True
replay-buffer-size: 1000000
epoch-num: 500
actor-weight-decay: 1e-06
max-path-step: 5000
categorical-distribution: {'n_atoms': 51, 'v_max': 250, 'v_min': -10}
expert-index: None
max-episode-num: 5000000
train-step-num: 1
render-eval: False
max-test-time: 10
env-id: HumanoidBalanceFilter-v0
critic-l2-reg: 0.0003
rollout-step-num: 1
actor-lr: 0.0003
imitation-weight: 1.0
n-step: 1
interpolation: False
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
task-weight: 0.0
reward-scale: 0.1
loss-output-smooth-coeff: 2.0
expert-num: 4
epoch-step-num: 5000000
total-step-num: 2500000000
critic-layer-size: [256, 256]
state-dim: 18
action-dim: 12
gating-index: None
loss-entropy-coeff: 0.0
critic-weight-decay: 1e-06
HLC-frequency: 25
actor-layer-size: [256, 256]
max-train-time: 10
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
critic-activation-fn: ['relu', 'relu', 'None']
max-path-num: 20
max-step-num: 2500000000
batch-size: 128
loss-output-bound-coeff: 0.0
