actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
interpolation: False
rollout-step-num: 1
actor-lr: 0.0003
max-test-time: 10
loss-output-smooth-coeff: 2.0
categorical-distribution: {'v_max': 250, 'n_atoms': 51, 'v_min': -10}
critic-l2-reg: 0.0003
critic-weight-decay: 1e-06
HLC-frequency: 25
squash-action: True
epoch-step-num: 5000000
max-step-num: 2500000000
replay-start-size: 10000
gating-layer-size: [32, 32]
render-eval: False
tau: 0.001
critic-activation-fn: ['relu', 'relu', 'None']
max-path-num: 20
loss-output-bound-coeff: 0.0
actor-layer-size: [256, 256]
epoch-num: 500
action-dim: 12
actor-l2-reg: 0.0003
filter-action: True
max-train-time: 10
task-weight: 0.0
critic-lr: 0.0003
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
n-step: 1
state-dim: 18
replay-ratio: 1
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
LLC-frequency: 500
loss-entropy-coeff: 0.0
loss-output-diff-coeff: 0
total-step-num: 2500000000
prioritized-exp-replay: True
train-step-num: 1
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
batch-size: 128
joint-interpolation: True
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
actor-activation-fn: ['relu', 'relu', 'None']
gamma: 0.995
expert-index: None
Physics-frequency: 1000
actor-weight-decay: 1e-06
max-episode-num: 5000000
env-id: HumanoidBalanceFilter-v0
gating-index: None
imitation-weight: 1.0
expert-num: 4
test-num: 4
record-start-size: 10000.0
filter-torque: False
max-path-step: 5000
bullet-default-PD: False
gating-activation-fn: ['relu', 'relu', 'None']
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
critic-layer-size: [256, 256]
reward-scale: 0.1
replay-buffer-size: 1000000
