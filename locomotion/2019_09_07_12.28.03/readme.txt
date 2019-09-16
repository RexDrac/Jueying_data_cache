loss-output-smooth-coeff: 1.0
action-dim: 12
gating-layer-size: [32, 32]
actor-weight-decay: 1e-06
loss-entropy-coeff: 0.0
replay-ratio: 1
filter-action: True
filter-torque: False
gating-activation-fn: ['relu', 'relu', 'None']
train-step-num: 1
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
interpolation: False
record-start-size: 10000.0
actor-lr: 0.0003
prioritized-exp-replay: True
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
total-step-num: 2500000000
env-id: HumanoidBalanceFilter-v0
expert-index: None
render-eval: False
dsr-gait-freq: 1.667
replay-buffer-size: 1000000
gamma: 0.955
imitation-weight: 0.5
squash-action: True
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
max-test-time: 10
max-train-time: 10
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
critic-activation-fn: ['relu', 'relu', 'None']
Physics-frequency: 1000
joint-interpolation: True
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
actor-activation-fn: ['relu', 'relu', 'None']
gating-index: None
max-episode-num: 5000000
tau: 0.001
critic-layer-size: [256, 256]
test-num: 4
HLC-frequency: 25
max-path-num: 20
bullet-default-PD: False
critic-l2-reg: 0.0003
loss-output-bound-coeff: 0.0
LLC-frequency: 500
state-dim: 23
batch-size: 128
task-weight: 0.5
dsr-gait-period: 0.6
loss-output-diff-coeff: 0
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
n-step: 1
rollout-step-num: 1
categorical-distribution: {'n_atoms': 51, 'v_min': -10, 'v_max': 250}
max-step-num: 2500000000
replay-start-size: 10000
expert-num: 4
actor-layer-size: [256, 256]
critic-weight-decay: 1e-06
reward-scale: 0.1
epoch-step-num: 5000000
max-path-step: 5000
actor-l2-reg: 0.0003
epoch-num: 500
critic-lr: 0.0003
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
