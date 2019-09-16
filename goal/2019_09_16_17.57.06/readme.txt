loss-output-bound-coeff: 0.0
critic-weight-decay: 1e-06
actor-layer-size: [256, 256]
replay-start-size: 10000
categorical-distribution: {'n_atoms': 51, 'v_min': -10, 'v_max': 250}
n-step: 1
gating-layer-size: [32, 32]
actor-activation-fn: ['relu', 'relu', 'None']
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
max-test-time: 10
critic-lr: 0.0003
expert-index: None
replay-buffer-size: 1000000
max-episode-num: 5000000
test-num: 4
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
filter-torque: False
render-eval: False
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
critic-l2-reg: 0.0003
loss-output-diff-coeff: 0
loss-output-smooth-coeff: 2.0
actor-weight-decay: 1e-06
HLC-frequency: 25
task-weight: 0.5
Physics-frequency: 1000
state-dim: 25
critic-activation-fn: ['relu', 'relu', 'None']
train-step-num: 1
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
expert-num: 4
replay-ratio: 1
gating-activation-fn: ['relu', 'relu', 'None']
actor-lr: 0.0003
imitation-weight: 0.5
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
max-train-time: 10
critic-layer-size: [256, 256]
epoch-num: 500
record-start-size: 10000.0
epoch-step-num: 5000000
interpolation: False
action-dim: 12
max-path-num: 20
rollout-step-num: 1
joint-interpolation: True
LLC-frequency: 500
total-step-num: 2500000000
squash-action: True
gamma: 0.955
actor-l2-reg: 0.0003
loss-entropy-coeff: 0.0
filter-action: True
bullet-default-PD: False
tau: 0.001
dsr-gait-period: 0.6
reward-scale: 0.1
max-step-num: 2500000000
prioritized-exp-replay: True
gating-index: None
batch-size: 128
dsr-gait-freq: 1.667
max-path-step: 5000
env-id: HumanoidBalanceFilter-v0
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
