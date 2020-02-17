actor-weight-decay: 1e-06
expert-index: None
interpolation: False
loss-output-smooth-coeff: 2.0
gating-index: None
categorical-distribution: {'n_atoms': 51, 'v_max': 250, 'v_min': -10}
max-step-num: 2500000000
actor-layer-size: [256, 256]
max-path-num: 20
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
action-dim: 12
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
rollout-step-num: 1
actor-lr: 0.0003
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
task-weight: 0.0
critic-layer-size: [256, 256]
critic-activation-fn: ['relu', 'relu', 'None']
joint-interpolation: True
Physics-frequency: 1000
record-start-size: 10000.0
total-step-num: 2500000000
HLC-frequency: 25
LLC-frequency: 500
epoch-num: 500
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
expert-num: 4
train-step-num: 1
n-step: 1
loss-entropy-coeff: 0.0
replay-ratio: 1
env-id: HumanoidBalanceFilter-v0
loss-output-bound-coeff: 0.0
render-eval: False
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
bullet-default-PD: False
state-dim: 18
actor-activation-fn: ['relu', 'relu', 'None']
critic-lr: 0.0003
filter-action: True
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
filter-torque: False
imitation-weight: 1.0
squash-action: True
replay-buffer-size: 1000000
max-episode-num: 5000000
tau: 0.001
max-path-step: 5000
max-train-time: 10
gating-activation-fn: ['relu', 'relu', 'None']
prioritized-exp-replay: True
replay-start-size: 10000
test-num: 4
gamma: 0.995
epoch-step-num: 5000000
reward-scale: 0.1
batch-size: 128
loss-output-diff-coeff: 0
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
actor-l2-reg: 0.0003
critic-weight-decay: 1e-06
max-test-time: 10
gating-layer-size: [32, 32]
critic-l2-reg: 0.0003
