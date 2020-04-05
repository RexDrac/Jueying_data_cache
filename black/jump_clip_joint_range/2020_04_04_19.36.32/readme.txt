train-step-num: 1
loss-entropy-coeff: 0.0
interpolation: False
filter-torque: False
actor-weight-decay: 1e-06
gating-activation-fn: ['relu', 'relu', 'None']
LLC-frequency: 500
actor-layer-size: [256, 256]
n-step: 1
gating-index: None
gamma: 0.955
filter-action: True
dsr-gait-freq: 1.667
HLC-frequency: 25
record-start-size: 10000.0
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
loss-output-smooth-coeff: 2.0
critic-activation-fn: ['relu', 'relu', 'None']
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
max-path-step: 5000
actor-activation-fn: ['relu', 'relu', 'None']
loss-output-bound-coeff: 0.0
gating-layer-size: [32, 32]
categorical-distribution: {'n_atoms': 51, 'v_max': 250, 'v_min': -10}
Physics-frequency: 1000
epoch-step-num: 5000000
critic-weight-decay: 1e-06
squash-action: True
max-step-num: 2500000000
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
replay-buffer-size: 1000000
tau: 0.001
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
action-dim: 12
batch-size: 128
joint-interpolation: True
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
actor-l2-reg: 0.0003
task-weight: 0.5
epoch-num: 500
rollout-step-num: 1
test-num: 4
render-eval: False
critic-lr: 0.0003
critic-layer-size: [256, 256]
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
env-id: HumanoidBalanceFilter-v0
critic-l2-reg: 0.0003
bullet-default-PD: False
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
expert-num: 4
state-dim: 23
dsr-gait-period: 0.6
imitation-weight: 0.5
loss-output-diff-coeff: 0
reward-scale: 0.1
max-episode-num: 5000000
replay-ratio: 1
max-path-num: 20
expert-index: None
replay-start-size: 10000
max-test-time: 10
total-step-num: 2500000000
max-train-time: 10
actor-lr: 0.0003
prioritized-exp-replay: True
