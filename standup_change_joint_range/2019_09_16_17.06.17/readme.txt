squash-action: True
critic-activation-fn: ['relu', 'relu', 'None']
loss-output-smooth-coeff: 2.0
max-episode-num: 5000000
gating-index: None
actor-l2-reg: 0.0003
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
critic-l2-reg: 0.0003
max-path-step: 5000
reward-scale: 0.1
interpolation: False
LLC-frequency: 500
task-weight: 0.0
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
categorical-distribution: {'n_atoms': 51, 'v_max': 250, 'v_min': -10}
n-step: 1
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
critic-layer-size: [256, 256]
batch-size: 128
action-dim: 12
max-test-time: 10
loss-entropy-coeff: 0.0
train-step-num: 1
render-eval: False
bullet-default-PD: False
Physics-frequency: 1000
gating-layer-size: [32, 32]
expert-index: None
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
tau: 0.001
total-step-num: 2500000000
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
HLC-frequency: 25
gating-activation-fn: ['relu', 'relu', 'None']
max-step-num: 2500000000
loss-output-bound-coeff: 0.0
replay-ratio: 1
actor-weight-decay: 1e-06
actor-lr: 0.0003
replay-buffer-size: 1000000
loss-output-diff-coeff: 0
actor-activation-fn: ['relu', 'relu', 'None']
env-id: HumanoidBalanceFilter-v0
filter-torque: False
max-train-time: 10
epoch-num: 500
imitation-weight: 1.0
max-path-num: 20
joint-interpolation: True
prioritized-exp-replay: True
expert-num: 4
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -1.884   0.6981
  -0.5236 -1.884   0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
replay-start-size: 10000
epoch-step-num: 5000000
filter-action: True
gamma: 0.995
rollout-step-num: 1
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
critic-weight-decay: 1e-06
actor-layer-size: [256, 256]
state-dim: 18
record-start-size: 10000.0
critic-lr: 0.0003
test-num: 4
