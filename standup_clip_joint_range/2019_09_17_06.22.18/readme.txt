actor-activation-fn: ['relu', 'relu', 'None']
categorical-distribution: {'v_max': 250, 'n_atoms': 51, 'v_min': -10}
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
critic-lr: 0.0003
replay-start-size: 10000
max-path-num: 20
gating-layer-size: [32, 32]
gating-index: None
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
epoch-step-num: 5000000
gamma: 0.995
critic-l2-reg: 0.0003
expert-num: 4
loss-output-diff-coeff: 0
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
total-step-num: 2500000000
reward-scale: 0.1
actor-weight-decay: 1e-06
actor-l2-reg: 0.0003
max-episode-num: 5000000
state-dim: 18
actor-layer-size: [256, 256]
task-weight: 0.0
tau: 0.001
HLC-frequency: 25
critic-layer-size: [256, 256]
batch-size: 128
render-eval: False
replay-ratio: 1
action-dim: 12
env-id: HumanoidBalanceFilter-v0
train-step-num: 1
Physics-frequency: 1000
squash-action: True
loss-entropy-coeff: 0.0
gating-activation-fn: ['relu', 'relu', 'None']
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
interpolation: False
bullet-default-PD: False
filter-action: True
n-step: 1
critic-activation-fn: ['relu', 'relu', 'None']
prioritized-exp-replay: True
max-train-time: 10
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
rollout-step-num: 1
joint-interpolation: True
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
filter-torque: False
max-test-time: 10
critic-weight-decay: 1e-06
max-step-num: 2500000000
imitation-weight: 1.0
epoch-num: 500
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
record-start-size: 10000.0
loss-output-bound-coeff: 0.0
loss-output-smooth-coeff: 2.0
expert-index: None
max-path-step: 5000
replay-buffer-size: 1000000
test-num: 4
actor-lr: 0.0003
LLC-frequency: 500
