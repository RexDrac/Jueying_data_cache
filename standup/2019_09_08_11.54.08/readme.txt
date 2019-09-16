loss-output-bound-coeff: 0.0
critic-activation-fn: ['relu', 'relu', 'None']
imitation-weight: 1.0
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
LLC-frequency: 500
rollout-step-num: 1
epoch-num: 500
loss-output-diff-coeff: 0
reward-scale: 0.1
actor-activation-fn: ['relu', 'relu', 'None']
max-path-step: 5000
gamma: 0.995
max-test-time: 10
Physics-frequency: 1000
joint-interpolation: True
categorical-distribution: {'v_max': 250, 'n_atoms': 51, 'v_min': -10}
render-eval: False
max-train-time: 10
critic-weight-decay: 1e-06
test-num: 4
HLC-frequency: 25
actor-lr: 0.0003
gating-layer-size: [32, 32]
gating-index: None
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
critic-l2-reg: 0.0003
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
n-step: 1
action-dim: 12
replay-buffer-size: 1000000
filter-action: True
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
max-path-num: 20
critic-layer-size: [256, 256]
epoch-step-num: 5000000
tau: 0.001
task-weight: 0.0
max-episode-num: 5000000
expert-num: 4
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
prioritized-exp-replay: True
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
record-start-size: 10000.0
bullet-default-PD: False
expert-index: None
state-dim: 18
filter-torque: False
gating-activation-fn: ['relu', 'relu', 'None']
replay-ratio: 1
loss-entropy-coeff: 0.0
interpolation: False
replay-start-size: 10000
total-step-num: 2500000000
env-id: HumanoidBalanceFilter-v0
actor-weight-decay: 1e-06
critic-lr: 0.0003
max-step-num: 2500000000
squash-action: True
loss-output-smooth-coeff: 1.0
train-step-num: 1
actor-l2-reg: 0.0003
actor-layer-size: [256, 256]
batch-size: 128
