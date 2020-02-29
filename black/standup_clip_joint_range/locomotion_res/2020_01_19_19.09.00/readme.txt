action-dim: 12
actor-layer-size: [256, 256]
dsr-gait-period: 0.6
task-weight: 0.5
rollout-step-num: 1
interpolation: False
expert-num: 4
epoch-num: 500
critic-l2-reg: 0.0003
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
HLC-frequency: 25
imitation-weight: 0.5
actor-weight-decay: 1e-06
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
Physics-frequency: 1000
joint-interpolation: True
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
loss-entropy-coeff: 0.0
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
render-eval: False
squash-action: True
max-step-num: 2500000000
record-start-size: 10000.0
tau: 0.001
n-step: 1
gating-layer-size: [32, 32]
LLC-frequency: 500
expert-index: None
critic-layer-size: [256, 256]
gamma: 0.955
max-train-time: 10
actor-activation-fn: ['relu', 'relu', 'None']
loss-output-bound-coeff: 0.0
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
gating-index: None
replay-start-size: 10000
batch-size: 128
filter-torque: False
max-test-time: 10
prioritized-exp-replay: True
critic-activation-fn: ['relu', 'relu', 'None']
replay-ratio: 1
categorical-distribution: {'v_min': -10, 'v_max': 250, 'n_atoms': 51}
train-step-num: 1
loss-output-diff-coeff: 0
total-step-num: 2500000000
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
loss-output-smooth-coeff: 2.0
filter-action: True
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
max-path-num: 20
replay-buffer-size: 1000000
max-path-step: 5000
dsr-gait-freq: 1.667
critic-weight-decay: 1e-06
bullet-default-PD: False
epoch-step-num: 5000000
actor-l2-reg: 0.0003
actor-lr: 0.0003
gating-activation-fn: ['relu', 'relu', 'None']
max-episode-num: 5000000
state-dim: 23
test-num: 4
critic-lr: 0.0003
reward-scale: 0.1
env-id: HumanoidBalanceFilter-v0
