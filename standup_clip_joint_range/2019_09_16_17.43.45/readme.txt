filter-torque: False
joint-interpolation: True
record-start-size: 10000.0
max-step-num: 2500000000
max-test-time: 10
total-step-num: 2500000000
loss-output-smooth-coeff: 2.0
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
actor-l2-reg: 0.0003
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
max-path-step: 5000
action-dim: 12
max-path-num: 20
actor-activation-fn: ['relu', 'relu', 'None']
n-step: 1
tau: 0.001
render-eval: False
critic-lr: 0.0003
actor-layer-size: [256, 256]
expert-num: 4
rollout-step-num: 1
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
epoch-num: 500
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
bullet-default-PD: False
gating-index: None
batch-size: 128
critic-weight-decay: 1e-06
max-train-time: 10
epoch-step-num: 5000000
prioritized-exp-replay: True
gating-layer-size: [32, 32]
replay-start-size: 10000
reward-scale: 0.1
loss-output-diff-coeff: 0
test-num: 4
expert-index: None
HLC-frequency: 25
categorical-distribution: {'v_min': -10, 'n_atoms': 51, 'v_max': 250}
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
critic-activation-fn: ['relu', 'relu', 'None']
filter-action: True
squash-action: True
Physics-frequency: 1000
LLC-frequency: 500
env-id: HumanoidBalanceFilter-v0
train-step-num: 1
gamma: 0.995
gating-activation-fn: ['relu', 'relu', 'None']
actor-weight-decay: 1e-06
loss-entropy-coeff: 0.0
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
actor-lr: 0.0003
task-weight: 0.0
state-dim: 18
critic-l2-reg: 0.0003
replay-ratio: 1
loss-output-bound-coeff: 0.0
imitation-weight: 1.0
replay-buffer-size: 1000000
critic-layer-size: [256, 256]
max-episode-num: 5000000
interpolation: False
