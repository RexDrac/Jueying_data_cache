replay-buffer-size: 1000000
record-start-size: 10000.0
categorical-distribution: {'n_atoms': 51, 'v_max': 250, 'v_min': -10}
loss-output-smooth-coeff: 2.0
max-path-num: 20
actor-activation-fn: ['relu', 'relu', 'None']
critic-activation-fn: ['relu', 'relu', 'None']
env-id: HumanoidBalanceFilter-v0
max-test-time: 10
gating-activation-fn: ['relu', 'relu', 'None']
max-train-time: 10
train-step-num: 1
critic-layer-size: [256, 256]
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
critic-weight-decay: 1e-06
gating-index: None
reward-scale: 0.1
dsr-gait-freq: 1.667
prioritized-exp-replay: True
test-num: 4
max-path-step: 5000
epoch-num: 500
max-step-num: 2500000000
n-step: 1
state-dim: 23
filter-action: True
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
filter-torque: False
critic-l2-reg: 0.0003
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
actor-l2-reg: 0.0003
epoch-step-num: 5000000
task-weight: 0.5
loss-entropy-coeff: 0.0
bullet-default-PD: False
critic-lr: 0.0003
max-episode-num: 5000000
interpolation: False
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
replay-ratio: 1
total-step-num: 2500000000
expert-num: 4
HLC-frequency: 25
action-dim: 12
imitation-weight: 0.5
actor-layer-size: [256, 256]
gating-layer-size: [32, 32]
joint-interpolation: True
rollout-step-num: 1
tau: 0.001
Physics-frequency: 1000
gamma: 0.955
loss-output-bound-coeff: 0.0
squash-action: True
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
expert-index: None
actor-weight-decay: 1e-06
render-eval: False
dsr-gait-period: 0.6
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
replay-start-size: 10000
actor-lr: 0.0003
loss-output-diff-coeff: 0
LLC-frequency: 500
batch-size: 128
