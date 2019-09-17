imitation-weight: 1.0
expert-num: 4
env-id: HumanoidBalanceFilter-v0
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
bullet-default-PD: False
state-dim: 18
gating-index: None
max-path-num: 20
actor-activation-fn: ['relu', 'relu', 'None']
prioritized-exp-replay: True
critic-layer-size: [256, 256]
categorical-distribution: {'n_atoms': 51, 'v_max': 250, 'v_min': -10}
rollout-step-num: 1
reward-scale: 0.1
batch-size: 128
gamma: 0.995
loss-output-diff-coeff: 0
expert-index: None
gating-layer-size: [32, 32]
replay-start-size: 10000
max-train-time: 10
epoch-num: 500
max-step-num: 2500000000
epoch-step-num: 5000000
replay-buffer-size: 1000000
n-step: 1
loss-output-smooth-coeff: 1.0
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
actor-weight-decay: 1e-06
replay-ratio: 1
record-start-size: 10000.0
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
HLC-frequency: 25
max-path-step: 5000
loss-entropy-coeff: 0.0
action-dim: 12
max-test-time: 10
render-eval: False
max-episode-num: 5000000
LLC-frequency: 500
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
Physics-frequency: 1000
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
train-step-num: 1
critic-l2-reg: 0.0003
test-num: 4
squash-action: True
loss-output-bound-coeff: 0.0
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
task-weight: 0.0
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
critic-activation-fn: ['relu', 'relu', 'None']
joint-interpolation: True
filter-torque: False
interpolation: False
actor-lr: 0.0003
actor-layer-size: [256, 256]
critic-lr: 0.0003
filter-action: True
tau: 0.001
critic-weight-decay: 1e-06
total-step-num: 2500000000
actor-l2-reg: 0.0003
gating-activation-fn: ['relu', 'relu', 'None']
