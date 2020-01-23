record-start-size: 10000.0
task-weight: 0.0
critic-layer-size: [256, 256]
bullet-default-PD: False
LLC-frequency: 500
replay-start-size: 10000
expert-num: 4
replay-ratio: 1
expert-index: None
joint-interpolation: True
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
critic-weight-decay: 1e-06
n-step: 1
epoch-num: 500
categorical-distribution: {'v_max': 250, 'v_min': -10, 'n_atoms': 51}
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
action-dim: 12
render-eval: False
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
batch-size: 128
test-num: 4
critic-activation-fn: ['relu', 'relu', 'None']
rollout-step-num: 1
gating-activation-fn: ['relu', 'relu', 'None']
squash-action: True
imitation-weight: 1.0
filter-torque: False
critic-l2-reg: 0.0003
epoch-step-num: 5000000
actor-layer-size: [256, 256]
interpolation: False
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
max-path-num: 20
max-episode-num: 5000000
state-dim: 18
actor-lr: 0.0003
tau: 0.001
total-step-num: 2500000000
loss-output-diff-coeff: 0
filter-action: True
max-train-time: 10
loss-output-bound-coeff: 0.0
actor-activation-fn: ['relu', 'relu', 'None']
max-path-step: 5000
env-id: HumanoidBalanceFilter-v0
loss-entropy-coeff: 0.0
actor-l2-reg: 0.0003
max-test-time: 10
loss-output-smooth-coeff: 2.0
Physics-frequency: 1000
HLC-frequency: 25
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
gamma: 0.995
critic-lr: 0.0003
gating-layer-size: [32, 32]
replay-buffer-size: 1000000
reward-scale: 0.1
gating-index: None
max-step-num: 2500000000
actor-weight-decay: 1e-06
prioritized-exp-replay: True
train-step-num: 1
