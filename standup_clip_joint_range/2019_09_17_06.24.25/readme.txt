replay-start-size: 10000
max-test-time: 10
gating-layer-size: [32, 32]
Physics-frequency: 1000
loss-output-diff-coeff: 0
expert-index: None
render-eval: False
prioritized-exp-replay: True
epoch-num: 500
critic-layer-size: [256, 256]
batch-size: 128
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
total-step-num: 2500000000
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
max-episode-num: 5000000
actor-weight-decay: 1e-06
replay-ratio: 1
expert-num: 4
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
actor-activation-fn: ['relu', 'relu', 'None']
gating-activation-fn: ['relu', 'relu', 'None']
bullet-default-PD: False
loss-output-smooth-coeff: 2.0
categorical-distribution: {'v_max': 250, 'n_atoms': 51, 'v_min': -10}
replay-buffer-size: 1000000
gating-index: None
critic-weight-decay: 1e-06
max-step-num: 2500000000
tau: 0.001
critic-l2-reg: 0.0003
imitation-weight: 1.0
max-train-time: 10
critic-lr: 0.0003
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
loss-output-bound-coeff: 0.0
max-path-num: 20
test-num: 4
record-start-size: 10000.0
joint-interpolation: True
state-dim: 18
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
filter-torque: False
squash-action: True
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
train-step-num: 1
actor-lr: 0.0003
loss-entropy-coeff: 0.0
actor-layer-size: [256, 256]
critic-activation-fn: ['relu', 'relu', 'None']
task-weight: 0.0
env-id: HumanoidBalanceFilter-v0
LLC-frequency: 500
reward-scale: 0.1
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
HLC-frequency: 25
n-step: 1
filter-action: True
action-dim: 12
interpolation: False
actor-l2-reg: 0.0003
rollout-step-num: 1
max-path-step: 5000
epoch-step-num: 5000000
gamma: 0.995
