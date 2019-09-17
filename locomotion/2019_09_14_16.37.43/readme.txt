critic-lr: 0.0003
squash-action: True
tau: 0.001
loss-output-bound-coeff: 0.0
loss-entropy-coeff: 0.0
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
Physics-frequency: 1000
rollout-step-num: 1
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
gating-index: None
total-step-num: 2500000000
gating-activation-fn: ['relu', 'relu', 'None']
loss-output-smooth-coeff: 1.0
critic-weight-decay: 1e-06
HLC-frequency: 25
critic-l2-reg: 0.0003
max-path-num: 20
interpolation: False
action-dim: 12
env-id: HumanoidBalanceFilter-v0
epoch-num: 500
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
filter-action: True
bullet-default-PD: False
imitation-weight: 0.5
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
max-step-num: 2500000000
n-step: 1
epoch-step-num: 5000000
dsr-gait-freq: 1.667
critic-activation-fn: ['relu', 'relu', 'None']
expert-index: None
actor-lr: 0.0003
actor-l2-reg: 0.0003
replay-ratio: 1
LLC-frequency: 500
categorical-distribution: {'n_atoms': 51, 'v_max': 250, 'v_min': -10}
actor-activation-fn: ['relu', 'relu', 'None']
render-eval: False
state-dim: 23
replay-start-size: 10000
gating-layer-size: [32, 32]
max-train-time: 10
prioritized-exp-replay: True
joint-interpolation: True
reward-scale: 0.1
dsr-gait-period: 0.6
max-episode-num: 5000000
actor-weight-decay: 1e-06
batch-size: 128
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
filter-torque: False
max-test-time: 10
replay-buffer-size: 1000000
train-step-num: 1
loss-output-diff-coeff: 0
record-start-size: 10000.0
task-weight: 0.5
gamma: 0.955
test-num: 4
max-path-step: 5000
critic-layer-size: [256, 256]
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
expert-num: 4
actor-layer-size: [256, 256]
