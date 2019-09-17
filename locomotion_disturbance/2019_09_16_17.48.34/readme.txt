total-step-num: 2500000000
critic-l2-reg: 0.0003
max-step-num: 2500000000
record-start-size: 10000.0
interpolation: False
critic-activation-fn: ['relu', 'relu', 'None']
filter-action: True
rollout-step-num: 1
loss-output-smooth-coeff: 0.5
replay-ratio: 1
loss-output-diff-coeff: 0
expert-num: 4
categorical-distribution: {'n_atoms': 51, 'v_min': -10, 'v_max': 250}
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
test-num: 4
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
HLC-frequency: 25
dsr-gait-period: 0.6
gating-activation-fn: ['relu', 'relu', 'None']
loss-entropy-coeff: 0.0
expert-index: None
gating-index: None
replay-buffer-size: 1000000
action-dim: 12
reward-scale: 0.1
joint-interpolation: True
filter-torque: False
max-train-time: 10
epoch-num: 500
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
actor-activation-fn: ['relu', 'relu', 'None']
LLC-frequency: 500
gamma: 0.955
batch-size: 128
Physics-frequency: 1000
prioritized-exp-replay: True
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
env-id: HumanoidBalanceFilter-v0
dsr-gait-freq: 1.667
imitation-weight: 0.5
bullet-default-PD: False
max-path-step: 5000
critic-layer-size: [256, 256]
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
critic-lr: 0.0003
epoch-step-num: 5000000
state-dim: 23
actor-lr: 0.0003
squash-action: True
actor-weight-decay: 1e-06
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
loss-output-bound-coeff: 0.0
replay-start-size: 10000
tau: 0.001
critic-weight-decay: 1e-06
n-step: 1
actor-layer-size: [256, 256]
actor-l2-reg: 0.0003
task-weight: 0.5
render-eval: False
train-step-num: 1
gating-layer-size: [32, 32]
max-path-num: 20
max-test-time: 10
max-episode-num: 5000000
