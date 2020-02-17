reward-scale: 0.1
epoch-step-num: 5000000
critic-lr: 0.0003
max-step-num: 2500000000
tau: 0.001
env-id: HumanoidBalanceFilter-v0
gating-layer-size: [32, 32]
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
state-dim: 18
batch-size: 128
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
test-num: 4
actor-lr: 0.0003
prioritized-exp-replay: True
actor-weight-decay: 1e-06
actor-layer-size: [256, 256]
LLC-frequency: 500
squash-action: True
loss-entropy-coeff: 0.0
actor-l2-reg: 0.0003
max-episode-num: 5000000
max-train-time: 10
loss-output-diff-coeff: 0
gating-index: None
loss-output-smooth-coeff: 2.0
epoch-num: 500
critic-layer-size: [256, 256]
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
train-step-num: 1
max-test-time: 10
joint-interpolation: True
loss-output-bound-coeff: 0.0
critic-weight-decay: 1e-06
filter-action: True
render-eval: False
expert-num: 4
replay-start-size: 10000
critic-activation-fn: ['relu', 'relu', 'None']
task-weight: 0.0
expert-index: None
Physics-frequency: 1000
replay-buffer-size: 1000000
gating-activation-fn: ['relu', 'relu', 'None']
replay-ratio: 1
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
critic-l2-reg: 0.0003
action-dim: 12
record-start-size: 10000.0
interpolation: False
actor-activation-fn: ['relu', 'relu', 'None']
rollout-step-num: 1
gamma: 0.995
max-path-num: 20
total-step-num: 2500000000
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
bullet-default-PD: False
max-path-step: 5000
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
HLC-frequency: 25
categorical-distribution: {'v_min': -10, 'v_max': 250, 'n_atoms': 51}
imitation-weight: 1.0
n-step: 1
filter-torque: False
