actor-lr: 0.0003
expert-index: None
critic-lr: 0.0003
LLC-frequency: 500
categorical-distribution: {'v_min': -10, 'n_atoms': 51, 'v_max': 250}
loss-output-diff-coeff: 0
state-dim: 18
critic-activation-fn: ['relu', 'relu', 'None']
loss-output-smooth-coeff: 2.0
replay-start-size: 10000
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
filter-action: True
tau: 0.001
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
max-step-num: 2500000000
Physics-frequency: 1000
squash-action: True
rollout-step-num: 1
gating-index: None
epoch-num: 500
actor-activation-fn: ['relu', 'relu', 'None']
max-train-time: 10
total-step-num: 2500000000
actor-layer-size: [256, 256]
gating-layer-size: [32, 32]
reward-scale: 0.1
HLC-frequency: 25
critic-weight-decay: 1e-06
env-id: HumanoidBalanceFilter-v0
expert-num: 4
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
test-num: 4
gamma: 0.995
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
max-path-num: 20
filter-torque: False
render-eval: False
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
train-step-num: 1
joint-interpolation: True
replay-ratio: 1
loss-entropy-coeff: 0.0
batch-size: 128
n-step: 1
bullet-default-PD: False
task-weight: 0.0
epoch-step-num: 5000000
loss-output-bound-coeff: 0.0
imitation-weight: 1.0
critic-layer-size: [256, 256]
actor-weight-decay: 1e-06
replay-buffer-size: 1000000
max-test-time: 10
critic-l2-reg: 0.0003
actor-l2-reg: 0.0003
max-path-step: 5000
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -1.884   0.6981
  -0.5236 -1.884   0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
action-dim: 12
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
gating-activation-fn: ['relu', 'relu', 'None']
max-episode-num: 5000000
prioritized-exp-replay: True
record-start-size: 10000.0
interpolation: False
