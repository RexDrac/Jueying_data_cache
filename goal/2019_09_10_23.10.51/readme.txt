expert-num: 4
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
replay-start-size: 10000
loss-output-smooth-coeff: 1.0
categorical-distribution: {'n_atoms': 51, 'v_min': -10, 'v_max': 250}
train-step-num: 1
test-num: 4
actor-activation-fn: ['relu', 'relu', 'None']
critic-l2-reg: 0.0003
loss-output-diff-coeff: 0
actor-lr: 0.0003
loss-output-bound-coeff: 0.0
batch-size: 128
joint-interpolation: True
gating-index: None
expert-index: None
max-step-num: 2500000000
critic-weight-decay: 1e-06
prioritized-exp-replay: True
dsr-gait-freq: 1.667
task-weight: 0.5
max-path-step: 5000
tau: 0.001
epoch-num: 500
critic-activation-fn: ['relu', 'relu', 'None']
imitation-weight: 0.5
gating-activation-fn: ['relu', 'relu', 'None']
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
filter-torque: False
gating-layer-size: [32, 32]
epoch-step-num: 5000000
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
action-dim: 12
max-path-num: 20
max-test-time: 10
dsr-gait-period: 0.6
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
gamma: 0.955
bullet-default-PD: False
filter-action: True
env-id: HumanoidBalanceFilter-v0
render-eval: False
max-episode-num: 5000000
reward-scale: 0.1
HLC-frequency: 25
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
critic-layer-size: [256, 256]
n-step: 1
loss-entropy-coeff: 0.0
actor-l2-reg: 0.0003
rollout-step-num: 1
max-train-time: 10
Physics-frequency: 1000
squash-action: True
total-step-num: 2500000000
critic-lr: 0.0003
LLC-frequency: 500
state-dim: 25
replay-ratio: 1
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
actor-layer-size: [256, 256]
interpolation: False
actor-weight-decay: 1e-06
record-start-size: 10000.0
replay-buffer-size: 1000000
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
