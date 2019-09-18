expert-num: 4
train-step-num: 1
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
critic-lr: 0.0003
env-id: HumanoidBalanceFilter-v0
gating-activation-fn: ['relu', 'relu', 'None']
actor-activation-fn: ['relu', 'relu', 'None']
gating-layer-size: [32, 32]
loss-output-smooth-coeff: 2.0
max-test-time: 10
epoch-num: 500
squash-action: True
actor-layer-size: [256, 256]
critic-layer-size: [256, 256]
replay-ratio: 1
imitation-weight: 1.0
categorical-distribution: {'v_max': 250, 'n_atoms': 51, 'v_min': -10}
gating-index: None
n-step: 1
critic-l2-reg: 0.0003
record-start-size: 10000.0
epoch-step-num: 5000000
LLC-frequency: 500
max-train-time: 10
interpolation: False
critic-activation-fn: ['relu', 'relu', 'None']
batch-size: 128
actor-lr: 0.0003
gamma: 0.995
max-path-num: 20
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
rollout-step-num: 1
max-path-step: 5000
loss-output-diff-coeff: 0
action-dim: 12
actor-l2-reg: 0.0003
state-dim: 18
bullet-default-PD: False
filter-action: True
joint-interpolation: True
replay-buffer-size: 1000000
replay-start-size: 10000
loss-output-bound-coeff: 0.0
task-weight: 0.0
render-eval: False
test-num: 4
filter-torque: False
critic-weight-decay: 1e-06
reward-scale: 0.1
prioritized-exp-replay: True
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
HLC-frequency: 25
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
total-step-num: 2500000000
actor-weight-decay: 1e-06
Physics-frequency: 1000
expert-index: None
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
tau: 0.001
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
max-step-num: 2500000000
loss-entropy-coeff: 0.0
max-episode-num: 5000000
