Physics-frequency: 1000
bullet-default-PD: False
task-weight: 0.5
actor-activation-fn: ['relu', 'relu', 'None']
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
actor-l2-reg: 0.0003
filter-action: True
loss-output-smooth-coeff: 2.0
loss-entropy-coeff: 0.0
imitation-weight: 0.5
state-dim: 23
gating-layer-size: [32, 32]
epoch-num: 500
record-start-size: 10000.0
prioritized-exp-replay: True
max-train-time: 10
gating-index: None
categorical-distribution: {'n_atoms': 51, 'v_min': -10, 'v_max': 250}
critic-l2-reg: 0.0003
replay-buffer-size: 1000000
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
critic-activation-fn: ['relu', 'relu', 'None']
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
total-step-num: 2500000000
tau: 0.001
dsr-gait-period: 0.6
interpolation: False
critic-weight-decay: 1e-06
replay-ratio: 1
dsr-gait-freq: 1.667
critic-lr: 0.0003
HLC-frequency: 25
critic-layer-size: [256, 256]
gating-activation-fn: ['relu', 'relu', 'None']
max-step-num: 2500000000
squash-action: True
n-step: 1
action-dim: 12
batch-size: 128
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
actor-layer-size: [256, 256]
max-path-num: 20
reward-scale: 0.1
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
max-path-step: 5000
max-episode-num: 5000000
test-num: 4
env-id: HumanoidBalanceFilter-v0
loss-output-bound-coeff: 0.0
train-step-num: 1
expert-num: 4
render-eval: False
max-test-time: 10
expert-index: None
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
gamma: 0.955
LLC-frequency: 500
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
actor-lr: 0.0003
replay-start-size: 10000
loss-output-diff-coeff: 0
actor-weight-decay: 1e-06
epoch-step-num: 5000000
rollout-step-num: 1
joint-interpolation: True
filter-torque: False
