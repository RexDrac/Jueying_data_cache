HLC-frequency: 25
replay-buffer-size: 1000000
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
imitation-weight: 1.0
record-start-size: 10000.0
filter-action: True
squash-action: True
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
prioritized-exp-replay: True
replay-start-size: 10000
epoch-num: 500
actor-layer-size: [256, 256]
critic-activation-fn: ['relu', 'relu', 'None']
actor-weight-decay: 1e-06
interpolation: False
max-episode-num: 5000000
env-id: HumanoidBalanceFilter-v0
action-dim: 12
train-step-num: 1
critic-l2-reg: 0.0003
epoch-step-num: 5000000
gamma: 0.995
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
total-step-num: 2500000000
rollout-step-num: 1
actor-activation-fn: ['relu', 'relu', 'None']
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
max-path-step: 5000
replay-ratio: 1
bullet-default-PD: False
loss-output-bound-coeff: 0.0
critic-layer-size: [256, 256]
max-step-num: 2500000000
critic-lr: 0.0003
LLC-frequency: 500
reward-scale: 0.1
test-num: 4
batch-size: 128
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
critic-weight-decay: 1e-06
state-dim: 18
Physics-frequency: 1000
gating-activation-fn: ['relu', 'relu', 'None']
max-path-num: 20
render-eval: False
loss-entropy-coeff: 0.0
n-step: 1
tau: 0.001
actor-lr: 0.0003
expert-num: 4
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
categorical-distribution: {'n_atoms': 51, 'v_max': 250, 'v_min': -10}
max-test-time: 10
gating-index: None
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
task-weight: 0.0
expert-index: None
filter-torque: False
actor-l2-reg: 0.0003
max-train-time: 10
loss-output-diff-coeff: 0
gating-layer-size: [32, 32]
loss-output-smooth-coeff: 2.0
joint-interpolation: True
