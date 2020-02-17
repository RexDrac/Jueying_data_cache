imitation-weight: 0.5
joint-interpolation: True
replay-buffer-size: 1000000
env-id: HumanoidBalanceFilter-v0
loss-output-bound-coeff: 0.0
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
max-train-time: 10
gating-layer-size: [32, 32]
epoch-step-num: 5000000
critic-layer-size: [256, 256]
total-step-num: 2500000000
batch-size: 128
gating-activation-fn: ['relu', 'relu', 'None']
rollout-step-num: 1
prioritized-exp-replay: True
gamma: 0.955
task-weight: 0.5
reward-scale: 0.1
max-episode-num: 5000000
expert-index: None
action-dim: 12
train-step-num: 1
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
state-dim: 23
bullet-default-PD: False
record-start-size: 10000.0
epoch-num: 500
Physics-frequency: 1000
max-step-num: 2500000000
interpolation: False
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
max-path-num: 20
replay-start-size: 10000
loss-output-diff-coeff: 0
LLC-frequency: 500
test-num: 4
actor-activation-fn: ['relu', 'relu', 'None']
critic-weight-decay: 1e-06
critic-lr: 0.0003
render-eval: False
replay-ratio: 1
loss-output-smooth-coeff: 2.0
actor-l2-reg: 0.0003
tau: 0.001
critic-activation-fn: ['relu', 'relu', 'None']
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
n-step: 1
actor-lr: 0.0003
max-test-time: 10
HLC-frequency: 25
critic-l2-reg: 0.0003
actor-weight-decay: 1e-06
max-path-step: 5000
filter-action: True
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
filter-torque: False
dsr-gait-period: 0.6
gating-index: None
actor-layer-size: [256, 256]
squash-action: True
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
expert-num: 4
dsr-gait-freq: 1.667
categorical-distribution: {'n_atoms': 51, 'v_min': -10, 'v_max': 250}
loss-entropy-coeff: 0.0
