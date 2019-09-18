n-step: 1
filter-torque: False
record-start-size: 10000.0
replay-ratio: 1
LLC-frequency: 500
critic-lr: 0.0003
env-id: HumanoidBalanceFilter-v0
total-step-num: 2500000000
reward-scale: 0.1
critic-weight-decay: 1e-06
batch-size: 128
actor-activation-fn: ['relu', 'relu', 'None']
rollout-step-num: 1
critic-layer-size: [256, 256]
categorical-distribution: {'v_min': -10, 'n_atoms': 51, 'v_max': 250}
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
critic-l2-reg: 0.0003
loss-output-bound-coeff: 0.0
HLC-frequency: 25
max-step-num: 2500000000
gating-layer-size: [32, 32]
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
max-train-time: 10
tau: 0.001
squash-action: True
loss-output-smooth-coeff: 2.0
imitation-weight: 1.0
gating-activation-fn: ['relu', 'relu', 'None']
bullet-default-PD: False
actor-layer-size: [256, 256]
joint-interpolation: True
render-eval: False
epoch-num: 500
max-path-num: 20
expert-index: None
gating-index: None
interpolation: False
filter-action: True
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
action-dim: 12
critic-activation-fn: ['relu', 'relu', 'None']
actor-l2-reg: 0.0003
epoch-step-num: 5000000
Physics-frequency: 1000
max-episode-num: 5000000
expert-num: 4
loss-output-diff-coeff: 0
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
task-weight: 0.0
prioritized-exp-replay: True
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
max-path-step: 5000
replay-buffer-size: 1000000
actor-weight-decay: 1e-06
train-step-num: 1
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
max-test-time: 10
replay-start-size: 10000
loss-entropy-coeff: 0.0
test-num: 4
state-dim: 18
actor-lr: 0.0003
gamma: 0.995
