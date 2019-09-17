env-id: HumanoidBalanceFilter-v0
render-eval: False
joint-interpolation: True
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
state-dim: 18
action-dim: 12
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
Physics-frequency: 1000
LLC-frequency: 500
HLC-frequency: 25
bullet-default-PD: False
gating-layer-size: [32, 32]
gating-activation-fn: ['relu', 'relu', 'None']
gating-index: None
expert-index: None
expert-num: 4
batch-size: 128
gamma: 0.995
tau: 0.001
n-step: 1
categorical-distribution: {'v_min': -10, 'v_max': 250, 'n_atoms': 51}
critic-layer-size: [256, 256]
critic-activation-fn: ['relu', 'relu', 'None']
critic-lr: 0.0003
critic-weight-decay: 1e-06
critic-l2-reg: 0.0003
actor-layer-size: [256, 256]
actor-activation-fn: ['relu', 'relu', 'None']
actor-lr: 0.0003
actor-weight-decay: 1e-06
actor-l2-reg: 0.0003
squash-action: True
max-path-num: 20
max-path-step: 5000
replay-ratio: 1
loss-entropy-coeff: 0.0
loss-output-bound-coeff: 0.0
loss-output-smooth-coeff: 2.0
loss-output-diff-coeff: 0
prioritized-exp-replay: True
replay-buffer-size: 1000000
replay-start-size: 10000
record-start-size: 10000.0
reward-scale: 0.1
epoch-num: 500
epoch-step-num: 5000000
total-step-num: 2500000000
max-train-time: 10
max-test-time: 10
test-num: 4
rollout-step-num: 1
train-step-num: 1
max-episode-num: 5000000
max-step-num: 2500000000
imitation-weight: 1.0
task-weight: 0.0
filter-torque: False
interpolation: False
filter-action: True
