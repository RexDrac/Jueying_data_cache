categorical-distribution: {'n_atoms': 51, 'v_max': 250, 'v_min': -10}
replay-ratio: 1
actor-weight-decay: 1e-06
epoch-num: 500
gating-activation-fn: ['relu', 'relu', 'None']
reward-scale: 0.1
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -1.884   0.6981
  -0.5236 -1.884   0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
expert-num: 4
state-dim: 18
batch-size: 128
Physics-frequency: 1000
interpolation: False
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
critic-weight-decay: 1e-06
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
gating-index: None
loss-output-bound-coeff: 0.0
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
critic-activation-fn: ['relu', 'relu', 'None']
epoch-step-num: 5000000
render-eval: False
action-dim: 12
filter-action: True
loss-output-smooth-coeff: 2.0
filter-torque: False
LLC-frequency: 500
replay-start-size: 10000
task-weight: 0.0
train-step-num: 1
expert-index: None
joint-interpolation: True
max-step-num: 2500000000
critic-layer-size: [256, 256]
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
max-path-num: 20
HLC-frequency: 25
critic-l2-reg: 0.0003
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
max-train-time: 10
replay-buffer-size: 1000000
actor-activation-fn: ['relu', 'relu', 'None']
loss-output-diff-coeff: 0
gamma: 0.995
loss-entropy-coeff: 0.0
actor-l2-reg: 0.0003
bullet-default-PD: False
test-num: 4
max-test-time: 10
env-id: HumanoidBalanceFilter-v0
rollout-step-num: 1
imitation-weight: 1.0
n-step: 1
record-start-size: 10000.0
actor-layer-size: [256, 256]
critic-lr: 0.0003
prioritized-exp-replay: True
tau: 0.001
gating-layer-size: [32, 32]
total-step-num: 2500000000
squash-action: True
max-episode-num: 5000000
actor-lr: 0.0003
max-path-step: 5000
